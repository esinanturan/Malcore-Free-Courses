<p align="center">
    <img src="../.github/radare2-cheatsheet.jpg" height="73" width="171">
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)**

---

### Index

- [Command Line Options](#command-line-options)
- [Configuration Properties](#configuration-properties)
- [Basic Commands](#basic-commands)
- [Positioning](#positioning)
- [Block Size](#block-size)
- [JSON Output](#json-output)
- [Analyze](#analyze)
- [Information](#information)
- [Write](#write)
- [Flags](#flags)
- [Yank & Paste](#yank-and-paste)
- [Visual Mode](#visual-mode)
- [ROP](#rop)
- [Searching](#searching)
- [Comments & Defines](#comments-and-defines)
- [Magic Files](#magic-files)
- [Yara](#yara)
- [Zignatures](#zignatures)
- [Compare Files](#compare-files)
- [Graphs](#graphs)
- [Debugger](#debugger)
- [WebGUI (Enyo)](#webgui-enyo)
- [Radare2 Suite Commands](#radare2-suite-commands)
- [Shellcode Generator (ragg2)](#shellcode-generator-ragg2)
- [Executable Analysis (rabin2)](#executable-analysis-rabin2)
- [Program Launcher (rarun2)](#program-launcher-rarun2)

---

### Command Line Options

| **Commands** | Details                                                              |
|--------------|----------------------------------------------------------------------|
| `-L`         | List of supported IO plugins                                         |
| `-q`         | Exit after processing commands                                       |
| `-w`         | Write mode enabled                                                   |
| `-i [file]`  | Interprets an r2 script                                              |
| `-A`         | Analyze executable at load time                                      |
| `-n`         | Bare load, do not load executable info as the entrypoint             |
| `-c 'cmds'`  | Run r2 and execute commands                                          |
| `-p [prj]`   | Creates a project for the file being analyzed                        |
| `-`          | Opens r2 with the malloc plugin that provides a 512-byte memory area |

[Back to Index](#index)

---

### Configuration Properties

| **Commands**           | Details                             |
|------------------------|-------------------------------------|
| `e`                    | Returns configuration properties    |
| `e <property>`         | Check specific property             |
| `e <property>=<value>` | Change property value               |
| `e?`                   | Help about a configuration property |

[Back to Index](#index)

---

### Basic Commands

| **Commands**             | Details                                      |
|--------------------------|----------------------------------------------|
| Command chaining         | `x 3;s+3;pi 3;s+3;pxo 4;`                    |
| Pipe with shell commands | <code>pd &#124; less</code>                  |
| Run shell commands       | `!cat /etc/passwd`                           |
| Escape to shell          | `!!command` and pass output to Radare buffer |

[Back to Index](#index)

---

### Positioning

| **Commands** | Details                          |
|--------------|----------------------------------|
| `s address`  | Move cursor to address or symbol |
| `s-5`        | Move 5 bytes backward            |
| `s-`         | Undo seek                        |
| `s+`         | Redo seek                        |

[Back to Index](#index)

---

### Block Size

| **Commands** | Details           |
|--------------|-------------------|
| `b size`     | Change block size |

[Back to Index](#index)

---

### JSON Output

| **Commands** | Details                                                       |
|--------------|---------------------------------------------------------------|
| `j`          | Most commands accept `j` to print their output in JSON format |

[Back to Index](#index)

---

### Analyze

| **Commands** | Details                                |
|--------------|----------------------------------------|
| `aa`         | Analyze all functions and basic blocks |
| `af`         | Analyze functions                      |
| `afl`        | List all functions                     |
| `afi`        | Info on current function               |
| `afr`        | Rename function                        |

[Back to Index](#index)

---

### Information

| **Commands** | Details                 |
|--------------|-------------------------|
| `iI`         | File info               |
| `iz`         | Strings in data section |
| `iS`         | Sections                |
| `is`         | Symbols                 |
| `il`         | Linked libraries        |
| `ii`         | Imports                 |
| `ie`         | Entrypoint              |

[Back to Index](#index)

---

### Write

| **Commands** | Details                                        |
|--------------|------------------------------------------------|
| `wx`         | Write hex values at the current offset         |
| `wa`         | Write assembly                                 |
| `wc`         | Write cache commit                             |
| `wv`         | Write value with endian conversion and padding |

[Back to Index](#index)

---

### Flags

| **Commands**       | Details                           |
|--------------------|-----------------------------------|
| `f`                | List flags                        |
| `f label @ offset` | Define a flag at an offset        |
| `fr`               | Rename flag                       |
| `fd`               | Return position from nearest flag |

[Back to Index](#index)

---

### Yank and Paste

| **Commands** | Details                                    |
|--------------|--------------------------------------------|
| `y n`        | Copy `n` bytes from current position       |
| `yp`         | Print yank buffer                          |
| `yy offset`  | Paste contents of yank buffer at an offset |

[Back to Index](#index)

---

### Visual Mode

| **Commands** | Details                          |
|--------------|----------------------------------|
| `V`          | Enter visual mode                |
| `q`          | Exit visual mode                 |
| `hjkl`       | Move around while in visual mode |
| `o`          | Go to offset                     |

[Back to Index](#index)

---

### ROP

| **Commands** | Details                      |
|--------------|------------------------------|
| `/R opcodes` | Search for opcodes           |
| `/a`         | Search for assembly          |
| `pda`        | Returns a library of gadgets |

[Back to Index](#index)

---

### Searching

| **Commands**     | Details                     |
|------------------|-----------------------------|
| `/ bytes`        | Search for bytes            |
| `/m [magicfile]` | Search magic number headers |

[Back to Index](#index)

---

### Comments and Defines

| **Commands** | Details                           |
|--------------|-----------------------------------|
| `Cd [size]`  | Define as data                    |
| `C- [size]`  | Define as code                    |
| `CC`         | Add a new comment in console mode |

[Back to Index](#index)

---

### Magic Files

| **Commands**     | Details                     |
|------------------|-----------------------------|
| `pm`             | Print Magic files analysis  |
| `/m [magicfile]` | Search magic number headers |

[Back to Index](#index)

---

### Yara

| **Commands** | Details                                 |
|--------------|-----------------------------------------|
| `:yara scan` | Scan with Yara for detecting signatures |

[Back to Index](#index)

---

### Zignatures

| **Commands**                  | Details                |
|-------------------------------|------------------------|
| `zg <language> <output file>` | Generate zignatures    |
| `z`                           | Show loaded zignatures |

[Back to Index](#index)

---

### Compare Files

| **Commands**               | Details                             |
|----------------------------|-------------------------------------|
| `r2 -m 0xf0000 /etc/fstab` | Open source file                    |
| `cc offset`                | Diff by columns between two offsets |

[Back to Index](#index)

---

### Graphs

| **Commands**     | Details                                        |
|------------------|------------------------------------------------|
| `ag $$ > a.dot`  | Dump basic block graph to a file named `a.dot` |
| `agc $$ > b.dot` | Dump call graph to a file named `b.dot`        |

[Back to Index](#index)

---

### Debugger

| **Commands**                                  | Details                                                               |
|-----------------------------------------------|-----------------------------------------------------------------------|
| <code>r2 -d [pid&#124;cmd&#124;ptrace]</code> | Start r2 in debugger mode (if the comamnd contains spaces use quotes) |
| `dp`                                          | Show processes and threads                                            |
| `dc`                                          | Continue execution                                                    |
| `db address`                                  | Set a breakpoint                                                      |

[Back to Index](#index)

---

### WebGUI (Enyo)

| **Commands** | Details                  |
|--------------|--------------------------|
| `=h`         | Start the server         |
| `=H`         | Start server and browser |

[Back to Index](#index)

---

### Radare2 Suite Commands

| **Commands**         | Details                           |
|----------------------|-----------------------------------|
| `rax2 -e`            | Base conversion and endian change |
| `rahash2 -a entropy` | Show entropy per block            |
| `radiff2 -C`         | Code diffing                      |
| `rasm2 -d`           | Disassemble data                  |

[Back to Index](#index)

---

### Shellcode Generator (ragg2)

| **Commands**                 | Details                       |
|------------------------------|-------------------------------|
| `ragg2 -a x86 -b 32 -i exec` | Generate 32-bit x86 shellcode |

[Back to Index](#index)

---

### Executable Analysis (rabin2)

| **Commands** | Details         |
|--------------|-----------------|
| `rabin2 -I`  | Executable info |
| `rabin2 -s`  | Symbols         |

[Back to Index](#index)

---

### Program Launcher (rarun2)

| **Commands**                                              | Details                                                       |
|-----------------------------------------------------------|---------------------------------------------------------------|
| `r2 -b 32 -d rarun2 program=exp1 arg1=$(ragg2 -P 200 -r)` | Launch a program with args inside r2's debugger               |
| `r2 -d rarun2 program=/bin/cat stdin=$(python e.py)`      | runs /bin/cat with the output of exploit.py directed to stdin |

[Back to Index](#index)

---

