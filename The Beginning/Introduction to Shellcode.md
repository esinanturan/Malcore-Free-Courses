# Introduction to Shellcode

<div align="center">

<img src="../.github/img.png" alt="" height="500" width="600">

</div>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)**


**NOTE: This course assumes that you understand the basics of x86 assembly and C code.**

***

## What will be covered?

* [What the f\*ck is shellcode?](<Introduction to Shellcode.md#what-the-fck-is-shellcode>)
* [How does it work?](<Introduction to Shellcode.md#how-does-shellcode-work>)
* [Let's write some](<Introduction to Shellcode.md#lets-write-some-shellcode>)
* [Compiling shellcode](<Introduction to Shellcode.md#compiling-it>)
* [Adding it to your executable](<Introduction to Shellcode.md#adding-shellcode-to-your-attack>)
* [We out g](<Introduction to Shellcode.md#in-closing>)

***

## What the f\*ck is shellcode?

In a nutshell shellcode is a small piece of code used as a payload for exploitation of software.

Typically, shellcode is written in assembly language and is designed to be injected into memory. Its primary use is arbitrary code execution; however, it can be used for multiple other functions.

The purpose of using shellcode is to gain control of a system by injecting the said shellcode into the vulnerable process. It is usually carefully constructed and designed specifically for the individual attack it accomplishes. This is important because a lot of the time, shellcode must be refined per system.

***

## How does Shellcode work?

To explain how shellcode works I first need to provide you with an exploitable program. For this we will use a basic program that is vulnerable to a buffer overflow due to not checking lengths passed. The code is below:

```c
#include <stdio.h>
#include <string.h>


void no_length_check_function(char *input) {
    // add a buffer
    char buffer[100];
    // do not check the length of the input and copy
    strcpy(buffer, input);
}

// create the 'entrypoint' for the program that takes argc (argument count) and argv (argument variables) as the arguments 
int main(int argc, char *argv[]) {
    // pass the first argv (argv[1]) which will be the second argument IE: file.exe ARGUMENT1 to the vulnerable function
    no_length_check_function(argv[1]);
    // return because it's an int
    return 0;
}
```

This program, when compiled allows an attacker to control the EIP by passing more than 100 characters as the argument. We can create a pseudo shellcode to overwrite the EIP with the following:

```asm
xor eax, eax        ;"\x31\xc0"             
push eax            ;"\x50"                  
push "//sh"         ;"\x68\x2f\x2f\x73\x68"  
push "/bin"         ;"\x68\x2f\x62\x69\x6e"  
mov ebx, esp        ;"\x89\xe3"              
push eax            ;"\x50"                  
push ebx            ;"\x53"                  
mov ecx, esp        ;"\x89\xe1"              
cdq                 ;"\x99"                  
mov al, 0xb         ;(execve syscall number) ;"\xb0\x0b"              
int 0x80            ;(trigger syscall) ;"\xcd\x80"              
```

In theory what would happen is the following:

* The attacker fills the buffer; in this case it is 100 characters with whatever they want. In the scenario you could easily fill the buffer using something like `python -c 'print("A"*100)'`.
* The attacker overwrites the return address or EIP to point to the location of their shellcode.
* The overwritten EIP address now contains the shellcode address and the shellcode is executed.

It is important to note this explanation will most likely not be able to be compiled and most likely will not work. This is a pseudo example designed to explain to you how shellcode works and why it works.

***

## Let's write some Windows x86 assembly

Now that you have the basic idea, we will write a small Windows x86 assembly program that launches `calc.exe`. This version uses Windows API imports instead of hardcoded function addresses.

```asm
section .text
    global _start

    extern _WinExec@8
    extern _ExitProcess@4

_start:
    xor eax, eax
    push eax
    push 0x6578652e     ; "exe."
    push 0x636c6163     ; "calc"
    mov ebx, esp

    push 1              ; SW_SHOWNORMAL
    push ebx            ; "calc.exe"
    call _WinExec@8

    push 0
    call _ExitProcess@4
```

To compile this, you will need two tools:

1. [NASM](https://www.nasm.us/) — an assembler for Intel x86 and x86-64 assembly.
2. [MinGW-w64](https://www.mingw-w64.org/downloads/) — provides GCC and Windows import libraries.

You can install both using Chocolatey or download them from their official websites. After installation, make sure both tools are available in your system `PATH`.

This example is written for **32-bit Windows**, so you need a 32-bit MinGW-w64 toolchain. Your GCC target should look like this:

```bash
i686-w64-mingw32
```

You can check your current GCC target with:

```bash
gcc -dumpmachine
```

If it shows this instead:

```bash
x86_64-w64-mingw32
```

then you are using a 64-bit MinGW-w64 toolchain. That will not link this 32-bit object file unless you also have the 32-bit libraries installed.

---

## Compiling it

Save the assembly code as:

```text
test_calc.asm
```

Then assemble it with NASM:

```bash
nasm -f win32 .\test_calc.asm -o test_calc.o
```

NASM should produce no output if the command succeeds. This creates a 32-bit Windows object file named:

```text
test_calc.o
```

The `-f win32` option tells NASM to generate a 32-bit PE/COFF object file.

Next, link the object file with GCC:

```bash
gcc -m32 -o test_calc.exe .\test_calc.o -nostdlib -lkernel32 "-Wl,-e,_start"
```

This command does the following:

* `-m32` tells GCC to create a 32-bit executable.
* `-o test_calc.exe` sets the output file name.
* `.\test_calc.o` is the object file produced by NASM.
* `-nostdlib` prevents GCC from linking the normal C runtime startup files.
* `-lkernel32` links against `kernel32.dll`, which provides `WinExec` and `ExitProcess`.
* `"-Wl,-e,_start"` tells the linker to use `_start` as the program entry point.

The quotes around `"-Wl,-e,_start"` are important in PowerShell because commas can be parsed specially.

If you get an error like this:

```text
skipping incompatible ... libkernel32.a
cannot find -lkernel32
```

then you are trying to link a 32-bit object file with a 64-bit MinGW-w64 toolchain. Use a 32-bit MinGW-w64 toolchain instead.

---

## Inspecting the object file

You can inspect the object file with `objdump`:

```bash
objdump -d .\test_calc.o
```

Example output:

```asm
.\test_calc.o:     file format pe-i386


Disassembly of section .text:

00000000 <_start>:
   0:   31 c0                   xor    %eax,%eax
   2:   50                      push   %eax
   3:   68 2e 65 78 65          push   $0x6578652e
   8:   68 63 61 6c 63          push   $0x636c6163
   d:   89 e3                   mov    %esp,%ebx
   f:   6a 01                   push   $0x1
  11:   53                      push   %ebx
  12:   e8 00 00 00 00          call   17 <_start+0x17>
  17:   6a 00                   push   $0x0
  19:   e8 00 00 00 00          call   1e <_start+0x1e>
```

The two `call` instructions may appear as:

```asm
e8 00 00 00 00
```

This is normal in an object file. The calls have not been resolved yet because `_WinExec@8` and `_ExitProcess@4` are external symbols. The linker resolves these references when it creates the final executable.

You can view the relocation entries with:

```bash
objdump -r .\test_calc.o
```

Example output:

```text
RELOCATION RECORDS FOR [.text]:
OFFSET   TYPE              VALUE
00000013 DISP32            _WinExec@8
0000001a DISP32            _ExitProcess@4
```

These relocation entries show that the object file contains references to imported Windows API functions that still need to be resolved during linking.

---

## Inspecting the final executable

After linking, inspect the executable with:

```bash
objdump -p .\test_calc.exe
```

Look for the import table. You should see imports from `KERNEL32.dll`, including:

```text
WinExec
ExitProcess
```

You can also disassemble the final executable:

```bash
objdump -d .\test_calc.exe
```

At this stage, the linker has produced a valid Windows PE executable that imports the required functions from `kernel32.dll`.

---

## Important note

This example is Windows x86 assembly that builds into a PE executable. It is not standalone position-independent shellcode.

Because the code uses imported symbols:

```asm
extern _WinExec@8
extern _ExitProcess@4
```

If you still want to view the raw instruction bytes from the object file, you can use `objdump`:

```bash
objdump -d .\test_calc.o
```

Example output:

```asm
.\test_calc.o:     file format pe-i386


Disassembly of section .text:

00000000 <_start>:
   0:   31 c0                   xor    %eax,%eax
   2:   50                      push   %eax
   3:   68 2e 65 78 65          push   $0x6578652e
   8:   68 63 61 6c 63          push   $0x636c6163
   d:   89 e3                   mov    %esp,%ebx
   f:   6a 01                   push   $0x1
  11:   53                      push   %ebx
  12:   e8 00 00 00 00          call   17 <_start+0x17>
  17:   6a 00                   push   $0x0
  19:   e8 00 00 00 00          call   1e <_start+0x1e>
```

You can manually convert the opcode bytes into `\xNN` format:

```text
\x31\xc0\x50\x68\x2e\x65\x78\x65\x68\x63\x61\x6c\x63\x89\xe3\x6a\x01\x53\xe8\x00\x00\x00\x00\x6a\x00\xe8\x00\x00\x00\x00
```

However, this byte string is **not valid standalone shellcode**. The two calls are unresolved linker placeholders:

```asm
e8 00 00 00 00
```

Those calls refer to external symbols:

```asm
_WinExec@8
_ExitProcess@4
```

The object file does not contain the final addresses for those imports. The linker resolves them when it builds the final PE executable.

You can confirm this by checking the relocations:

```bash
objdump -r .\test_calc.o
```

Example output:

```text
.\test_calc.o:     file format pe-i386

RELOCATION RECORDS FOR [.text]:
OFFSET   TYPE              VALUE
00000013 DISP32            _WinExec@8
0000001a DISP32            _ExitProcess@4
```

So while you can extract the bytes from the object file, those bytes cannot be dropped into a C shellcode runner and expected to work. They depend on relocation and import resolution during linking.

## In closing

This course has provided you with the basics of how shellcode works, how to compile it, and how to launch it from within a C program. This course was designed specifically for starters to understand the basic concepts of shellcode and what it does. We hope you have found this course useful and understand it.

#### Support the Bible

Once again, this course is offered for free by The Perkins Cybersecurity Educational Fund! If you found this information valuable and want to support the continued development of the Malware Bible please consider:
- Donating to the Malware Bible Fund → [Donate Here](https://donorbox.org/malware-bible-fund)

#### Become a sponsor

These courses reach thousands of cybersecurity professionals, researchers, students, and teachers worldwide who actively engage in learning and advancing the field. Sponsoring our educational initiative not only supports free cybersecurity education but also places your brand in front of a highly technical and security-conscious audience.

Interested in partnering? Let's talk about how your organization can be featured in our future courses: [Contact us today!](https://perkinsfund.org/index.html#contact-us) Please view our [Sponsorship Packages](https://perkinsfund.org/donations#sponsor-table) for more details!
