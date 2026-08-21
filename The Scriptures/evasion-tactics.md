<p align="center">
    <img src="../.github/img_7.png"/>
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)

---

#### Sponsor

Special thanks to the sponsor of this course: [HelpMeWrk](https://helpmewrk.com/?utm_source=perkinsfund)!

<p align="center">
    <img src="../.github/sponsor_images/hmw.png">
</p>

Automated job searching tailored to your resume. Upload a resume, configure, and get related job matches sent to your inbox.

---

This course is a collection of interesting malware evasion tactics and explanations of how they work.

## Whitespace Steganography

This evasion tactic was discovered in a lightweight backdoor that was approximately 12 KB in size. It hides its command and control server using whitespace steganography inside the Desktop.ini file. You can find the original post [here](https://x.com/blackorbird/status/2088636459628831128).

Our recreation of this tactic was done in Rust and uses a marker while ignoring anything that is before the marker and reading whitespace and tab characters. It works as follows:

##### Encoder

Each whitespace character represents bits: a tab character (`\t`) represents `1` and a single space character (` `) represents `0`. Each input byte is represented by 8 bits. For example, the ASCII character `h` equals `0x68` which equals `01101000`, or in whitespace: `SPACE TAB TAB SPACE TAB SPACE SPACE SPACE`.

```rust
/// Encodes each byte as eight whitespace characters.
/// A `0` bit becomes a space, while a `1` bit becomes a tab.
/// Bits are processed from most significant to least significant.

fn encode_whitespace(data: &str) -> String {
    let mut out = String::new();

    for byte in data.bytes() {
        for bit in (0..8).rev() {
            if (byte >> bit) & 1 == 0 {
                out.push(' ');
            } else {
                out.push('\t');
            }
        }
    }
    out
}
```

This is significant because it shows that you not only have to look at the file, but also what the file _should_ look like.

##### Decoder

The decoder does the exact opposite of the encoder in this form:
```
spaces/tabs
    ↓
binary bits
    ↓
8-bit groups
    ↓
bytes
    ↓
UTF-8 string
```

The decoder source code would look something like this:

```rust
fn decode_whitespace(data: &str) -> Result<String, &'static str> {
    // Extract only spaces and tabs; these represent binary digits.
    // A space represents 0, while a tab represents 1.
    let bits: Vec<char> = data
        .chars()
        .filter(|c| *c == ' ' || *c == '\t')
        .collect();

    // Each byte requires exactly 8 bits.
    if bits.len() % 8 != 0 {
        return Err("Whitespace payload is not a multiple of 8 bits");
    }

    let mut bytes = Vec::new();

    // Process the whitespace payload one byte at a time.
    for chunk in bits.chunks(8) {
        let mut byte = 0u8;

        for c in chunk {
            // Shift existing bits left to make room for the next bit.
            byte <<= 1;

            match c {
                // A single space encodes binary 0.
                ' ' => {}

                // A tab encodes binary 1.
                '\t' => byte |= 1,

                // This cannot occur because the input was filtered above.
                _ => unreachable!(),
            }
        }

        // Store the reconstructed byte.
        bytes.push(byte);
    }

    // Convert the decoded bytes into UTF-8 text.
    // Return an error if the bytes do not form valid UTF-8.
    String::from_utf8(bytes)
        .map_err(|_| "Decoded data is not valid UTF-8")
}
```

##### Full example code

```rust
use clap::Parser;
use std::fs;
use std::io;
use std::path::{Path, PathBuf};

#[derive(Parser)]
#[command(version, about = "Arguments accepted by the program - Traceix was here")]
struct Args {
    #[arg(short, long)]
    file: PathBuf,

    #[arg(short, long)]
    url: String,
}
// marker is three new lines bc who tf puts three new lines in a ini file?
const MARKER: &str = "\n\n\n";


fn encode_whitespace(data: &str) -> String {
    /* encode the whitespace into a byte readable version using tabs and single space characters */
    let mut out = String::new();
    for byte in data.bytes() {
        for bit in (0..8).rev() {
            if (byte >> bit) & 1 == 0 {
                out.push(' ');
            } else {
                out.push('\t');
            }
        }
    }
    out
}


fn decode_whitespace(data: &str) -> Result<String, &'static str> {
    /* decode the tabs and single space characters so that we can get the original string */
    let bits: Vec<char> = data
        .chars()
        .filter(|c| *c == ' ' || *c == '\t')
        .collect();
    if bits.len() % 8 != 0 {
        return Err("Whitespace payload is not a multiple of 8 bits");
    }
    let mut bytes = Vec::new();
    for chunk in bits.chunks(8) {
        let mut byte = 0u8;
        for c in chunk {
            byte <<= 1;

            match c {
                ' ' => {}
                '\t' => byte |= 1,
                _ => unreachable!(),
            }
        }
        bytes.push(byte);
    }
    String::from_utf8(bytes)
        .map_err(|_| "Decoded data is not valid UTF-8")
}


fn write_file(path: &Path, value: &str) -> io::Result<()> {
    /* rewrite the file to add our encoded whitespace to the end of it */
    let visible = "\
[.ShellClassInfo]
LocalizedResourceName=@%SystemRoot%\\system32\\shell32.dll,-21769
IconResource=%SystemRoot%\\system32\\imageres.dll,-183";
    let encoded = encode_whitespace(value);
    let contents = format!("{visible}{MARKER}{encoded}");
    fs::write(path, contents)
}


fn read_file(path: &Path) -> io::Result<()> {
    /* read the file from after the marker so that we can grab our encoded c2 address */
    let contents = fs::read_to_string(path)?;
    let Some((_, encoded)) = contents.split_once(MARKER) else {
        eprintln!("No encoded payload found");
        return Ok(());
    };
    match decode_whitespace(encoded) {
        Ok(value) => println!("Decoded: {value:?}"),
        Err(e) => eprintln!("Decode error: {e}"),
    }
    Ok(())
}


fn main() -> io::Result<()> {
    let args = Args::parse();
    write_file(&args.file, &args.url)?;
    println!(
        "Wrote whitespace-encoded data to {}",
        args.file.display()
    );
    read_file(&args.file)?;
    Ok(())
}
```

##### Usage
```bash 
cargo run -- --file PATH --url URL
```

## Environmental Keying

This evasion tactic is a way that malware encrypts payloads using victim specific details. Such as:

- Machine name
- Domain

These become part of the decryption key and outside the intended target the encrypted blob will not be able to decrypt itself. This makes it so that these attacks will only work on certain environments and analysis is much harder to perform. Real world examples include:

- InvisiMole: Uses Windows DPAPI so components can only be decrypted on the specific compromised computer.
- APT41 malware: Derived part of an encryption key from the machine’s disk-volume serial number.
- PowerPunch: Generated a unique next-stage key from the victim’s volume serial number.
- ROKRAT: Required an expected hostname before executing and decrypting important strings.
- Winnti: Required a particular command-line parameter, then reused it as a decryption key.
- Gauss: A classic case involving an encrypted payload designed to unlock only under specific target-environment conditions.

Below is an Python code example that demonstrates the evasion tactic by making it only run when the variable `computer_name` is equal to `HelpMeWrk-Is-The-Best`:

```python
import base64
import hashlib
import socket
import sys

from cryptography.fernet import Fernet, InvalidToken


ENCRYPTED_BLOB = (
    b"gAAAAABqhGjaRhLj7lZ3cT4GMdEyWQc_Sv_HMRZr7vW0vzhz2IKUShPfy5nUGs3"
    b"l4BUvSeBiC-Nmxdx2e8I0oclyKBvV_8wNbQ8zBGhVpMwmWXWme0Tmmoo="
)


def derive_environment_key(computer_name):
    normalized_name = computer_name.casefold().encode("utf-8")
    digest = hashlib.sha256(normalized_name).digest()
    return base64.urlsafe_b64encode(digest)


def main():
    computer_name = socket.gethostname()
    environment_key = derive_environment_key(computer_name)

    try:
        plaintext = Fernet(environment_key).decrypt(ENCRYPTED_BLOB)
    except InvalidToken:
        sys.exit(
            f"Decryption failed: {computer_name!r} is not the intended computer."
        )

    print("Decrypted blob:", plaintext.decode("utf-8"))
```

This is a very narrow example but provides the basic understanding of how easily malware can be environmentally keyed. When the hostname for the above example is `HelpMeWrk-Is-The-Best` the encrypted blob can be decrypted and will output a message.

## Custom VM Obfuscation

This is a technique where the malware author translates its instructions into proprietary bytecode. It will then embed an interpreter that executes it. 

Real world examples include:
- FinFisher/FinSpy: used its own tiny fake CPU. The real instructions were turned into custom bytecode, and an embedded interpreter executed them.
- KoiVM malware: used KoiVM to convert normal .NET instructions into a custom virtual instruction set.
- VMProtect: can turn functions into proprietary bytecode that only VMProtect's embedded virtual machine understands.

This technique becomes interesting during reverse engineering because instead of seeing something like:
```nasm
mov
xor
call
jmp
```

The reverse engineer may see something along the lines of:
```nasm
BYTECODE_47
BYTECODE_A2
BYTECODE_19
BYTECODE_D1
```

This will force the RE to recreate the VM's instruction set to understand the protected program. An example of this:

```c
#include <stdio.h>
#include <stdint.h>

enum {
    OP_LOAD  = 0x01,
    OP_ADD   = 0x02,
    OP_XOR   = 0x03,
    OP_PRINT = 0x04,
    OP_HALT  = 0xFF
};

typedef struct {
    uint8_t *code;
    size_t ip;
    int reg;
} VM;

void run_vm(VM *vm)
{
    while (1) {

        // Fetch the next virtual opcode.
        uint8_t opcode = vm->code[vm->ip++];

        // Dispatch the opcode to its handler.
        switch (opcode) {

            // Load the next byte into the virtual register.
            case OP_LOAD: {
                uint8_t value = vm->code[vm->ip++];
                vm->reg = value;
                break;
            }

            // Add the next byte to the virtual register.
            case OP_ADD: {
                uint8_t value = vm->code[vm->ip++];
                vm->reg += value;
                break;
            }

            // XOR the virtual register with the next byte.
            case OP_XOR: {
                uint8_t value = vm->code[vm->ip++];
                vm->reg ^= value;
                break;
            }

            // Print the current virtual register value.
            case OP_PRINT:
                printf("VM register = %d\n", vm->reg);
                break;

            // Stop the virtual machine.
            case OP_HALT:
                return;

            default:
                printf("Unknown opcode: 0x%02X\n", opcode);
                return;
        }
    }
}

int main(void)
{
    /*
     * Equivalent normal logic:
     *
     * int x = 10;
     * x += 5;
     * x ^= 3;
     * printf("%d\n", x);
     */

    uint8_t bytecode[] = {
        OP_LOAD, 10,
        OP_ADD,   5,
        OP_XOR,   3,
        OP_PRINT,
        OP_HALT
    };

    // Initialize the VM and start at the first bytecode instruction.
    VM vm = {
        .code = bytecode,
        .ip = 0,
        .reg = 0
    };

    run_vm(&vm);

    return 0;
}
```
