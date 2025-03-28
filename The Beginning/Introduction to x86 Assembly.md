<p align="center">
    <img src="../.github/img_3.png"/>
</p>


**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/) in collaboration with the Malcore team: [https://m4lc.io/courses/register](https://m4lc.io/courses/register)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund and registering for Malcore. You can also join the Malcore Discord server here: [https://m4lc.io/courses/discord](https://m4lc.io/courses/discord)

Malcore offers free threat intel in our Discord via their custom designed Discord bot. Join the Discord to discuss this course in further detail or to ask questions.

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)

##### NOTE: This course assumes that you are using Linux and have nasm installed.

---

#### Sponsor

Special thanks to the sponsor of this course: [Maldev Academy](https://maldevacademy.com/?referrer=perkinsfund)!

<p align="center">
    <img src="../.github/sponsor_images/MD.png" width="554" height="217">
</p>

Offensive security and malware development training academy

---

# What will be covered?
- [What is x86 Assembly?](#what-is-x86-assembly)
- [Breakdown of the Registers](#registers)
- [Breakdown of the Stack](#the-stack)
- [Writing Code in x86 Assembly](#writing-code-in-x86-assembly)
- [Compiling x86 Assembly Files](#compiling-assembly-code)
- [That's all Folks](#in-closing)

---

# What is x86 Assembly?

In a nutshell assembly is a low-level programming language to write instructions that a CPU can directly execute. Each instruction in assembly is composed of a mnemonic (opcode), operand, and an address. Some instructions come with a prefix, suffix or flag.  

x86 in the name specifies the architecture of the language. There are multiple types of assembly languages for each CPU architecture and for each CPU. For example, Intel chips have different instructions than ARM chips.

This course is a semi deep dive into the x86 programming language and should provide the user with enough information on how assembly works to build a program successfully.

---

# Registers

In a sentence: registers are small storage locations in a CPU that's used to hold temporary data during execution.

Each register has a purpose. However, most of them can be used for general purposes or for various operations. In this section we will provide information on the registers in the x86 architecture.

### General purpose registers
- `EAX`
  - Purpose:
    - The Accumulator register.
  - Common usage:
    - It is normally used for arithmetic operations, such as: `add`, `sub`, `mul`. Also used to store calculations results.
  - Example of usage:
```asm
mov eax, 15 ; loads 15 into EAX register
add eax, 15 ; EAX register now holds 30
```
- `EBX`
  - Purpose:
    - The Base register
  - Common usage:
    - Usually used as a pointer to data in memory, but can also be used for arithmetic purposes.
  - Example of usage:
```asm
mov ebx, 0x6D616C636F7265 ; loads the memory address 0x6D616C636F7265 into EBX 
```
- `ECX`
  - Purpose:
    - The Counter register
  - Common usage:
    - Mostly used as a loop counter or for string/memory operations
  - Example of usage:
```asm
mov ecx, 10      ; load 10 in ec
loop_start:      ; create a loop
dec ecx          ; decrement from ecx (ecx = ecx - 1)
jnz loop_start   ; jump to the start of the loop and remove if ecx != 0
```
- `EDX`
  - Purpose:
    - The Data register
  - Common usage:
    - Works with the `eax` register for multiplication/division. Holds parts of large results/data.
  - Example of usage:
```asm
mov eax, 20       ; loads 20 in eax
mov edx, 4        ; loads 4 into edx
mul edx           ; multiply eax by edx
```

##### NOTE: It is worth mentioning that 32bit is smaller than 64bit to store which is why sometimes edx, and eax are used together to hold values.

---
### Pointer and index registers
- `ESI`
  - Purpose:
    - The Source register
  - Common usage:
    - Mostly used for string operations to hold source address of mnemonics like: `movsb`, `movsw`, `movsd`
  - Example of usage:
```asm
mov esi, 0x6D616C636F7265 ; load source address into ESI
```
- `EDI`
  - Purpose:
    - The Destination Index register
  - Common usage:
    - String operations to hold the destination address in similar instructions
  - Example of usage:
```asm
mov edi, 0x6D616C636F7265 ; load destination address into EDI
```
- `EBP`
  - Purpose:
    - Base Pointer register
  - Common usage:
    - Generally points to base of current stack frame. References function parameters and variables.
  - Example of usage:
```asm 
push ebp      ; save old base pointer
mov ebp, esp  ; set new base pointer to the current stack pointer
```
- `ESP`
  - Purpose
    - Stack Pointer register
  - Common usage:
    - Points to the top of the stack, automatically updated.
  - Example of usage:
```asm
lea eax, [msg]     ; loads 'msg' address into eax
push eax           ; push the eax address onto stack
mov ebx, [esp]     ; reference the top of the stack using esp
```
---
### Special Purpose Registers
- `EIP`
  - Purpose:
    - Instruction pointer
  - Common usage:
    - Holds the address of the next instruction to be executed. This register is not directly modifiable by most instructions. Can only be modified through control flow instructions such as: `jmp`, `call`, `ret`.

- `EFLAGS`
  - Purpose
    - Flag register
  - Common usage:
    - Stores status flags that indicate operation results.
  - Flags:
    - Zero Flag (ZF): operation is zero
    - Carry Flag (CF): operation results in a carry or borrow
    - Sign Flag (SF): operation is negative
---
### Table breakdown:

| Register | Purpose                    |
|----------|----------------------------|
| `EAX`    | Accumulator (arithmetic)   |
| `EBX`    | Base register              |
| `ECX`    | Counter (loops, shifts)    |
| `EDX`    | Data register              |
| `ESI`    | Source index               |
| `EDI`    | Destination index          |
| `ESP`    | Stack pointer              |
| `EBP`    | Base pointer (stack frame) |
| `EIP`    | Instruction pointer        |

---
# The Stack

Now that we've gotten the registers out of the way, we need to learn about the stack. What's the stack? Well, the stack is basically a piece of memory that operates by doing the last in first out (LIFO) principle. This principle is a data structure where the last item added is the first item to be removed. 

The stack is used to store temporary data such as addresses, local variables, and register states. The below image should provide you with a better understanding of the stack:

<pre>
+------------------+ ; the top of the stack (ESP)
|  Return Address  | ; return address pushed when function is called
+------------------+
| Local Variable 1 | ; local variable pushed into the stack
+------------------+
| Local Variable 2 | ; more temporary data is pushed
+------------------+
|       ...        | ; The stack grows downwards in memory
+------------------+
|   Previous EBP   | ; old base saved while entering new function
+------------------+
|  Function Arg 1  | ; arguments passed are placed on the stack
+------------------+ ; bottom of the stack
</pre>

Now if you don't fully understand this yet that's okay there's a lot of information quickly. Let's go through it. Basic principles are as follows:
- The stack grows downwards in memory, from higher address to lower address
- The `PUSH` mnemonic adds an item to the top of the stack.
- The `POP` mnemonic removes the most recent item that was added. For example:
```asm
; push mnemonic example
mov eax, 10    ; loads 10 into eax register
push eax       ; push eax (10) onto the top of the stack

; current stack:
; TOP OF STACK -> 10

mov ebx, 20    ; loads 20 into ebx register
push ebx       ; push ebx (20) onto the stack top of the stack

; curent stack:
; TOP OF STACK -> 20
;        10

; pop mnemonic example
pop ecx        ; pop the last item off the top of the stack

; current stack:
; TOP OF STACK -> 10

pop edx        ; pop the last item off the top of the stack

; curent stack:
; TOP OF STACK -> 

; the stack is now empty
```
- The `ESP` register is the stack pointer. This register tracks the top of the stack. So in the above example at the end, the register is `10` because we pushed 20 off the stack.
- When a function is called the arguments and the return address of the function is pushed to the stack as well.

So basically, as the stack grows downward in memory the `push` and `pop` mnemonics manage the stack by adding and removing items from the top of the stack while the `esp` register automatically tracks the top of the stack. 

---

# Writing code in x86 Assembly

When writing code in assembly you will be adding sections to the assembly code. These sections are used to organize the code into specific areas of memory. These areas of memory have different purposes during runtime. Let's go through the sections and their responsibilities:

### Common Section Information

| Section Name | Description                                                                | Info                                                                 | Notes                                                       |
|--------------|----------------------------------------------------------------------------|----------------------------------------------------------------------|-------------------------------------------------------------|
| `.text`      | Contains the code of the program                                           | Executable by the CPU                                                | Read-only to prevent modification                           |
| `.data`      | Houses the static data of the program that will be modified by the program | Usually stores globals and initialized data                          | Most likely will be read-write                              |
| `.bss`       | Stores uninitialized data                                                  | Variables sizes in the section are known but values are 0 at runtime | Saves memory because you don't need to initialize variables |
| `.rdata`     | Stores read only data                                                      | Data is not modified during execution                                | Primary purpose is to hold constant data                    |

By breaking a program apart into sections, it allows the processor to access each type more efficiently. Such as how modern processors cache information differently to optimize speed.

When the operating system loads the program it does the following:
- Loads the code marked as executable into memory
- Loads the data into memory segments that's marked as writeable
- Sets the permissions accordingly to help with performance and security

Basically, sections assemble code into readable, writeable, or readable and writeable segments to help the processor efficiently use memory, obtain higher levels of security, and provide easier management for both the assembler and the operating system. An example of sections is the following:

```asm
; initalized data section (data that will be used)
section .data 
    message db 'Hello, World!', 0  ; contains a null terminated string
    ...

; uninitialized data section (data that may be used)
section .bss 
    buffer resb 128  ; saves 128 bytes of memory for future use
    ...

; code section (data that will be executed)
section .text 
    global _start  ; contains the instructions that will be called

_start:
    ...  ; the 'function'                   
```

### Writing the code

Now that we understand sections and what they are for, we can start writing some code. For this course we will write a basic 'Hello, World!' program using x86 assembly.

```asm
; declare the entrypoint of the program itself
global _start
;
; the keyword global makes the label (in this case _start) accessible from outside the current program.
; This keyword tells the linker where the program starts
;

; initialized data section (readable and writeable data)
section .data
    ; align the data in a 2-byte boundary - allows better memory access 
	align 2
	
	; define a string followed by a newline character
	hello: db 'Hello world!', 0xa
	
	; calculate the length of the string by subtracing from the current address
	helloLen: equ $-hello 
;
; this section stores the data that will be used through the program. The align mnemonic ensures that the 
; string 'Hello, World!' is aligned on a 2-byte boundary for easier memory access. It also houses the length
; of the string.
;

; store uninitialized data
section .bss 
; 
; since there is no data that "may" be used, this section is empty
; 

; store the actual code of the program
section .text
	
	; define the entrypoint where the program starts execution
	_start:
	  
	  ; syscall for sys_write
  	  mov eax, 0x4 
  	  
  	  ; file descriptor for stdout
	  mov ebx, 0x1  
	  
	  ; address of the initialized string
	  mov ecx, hello  
	  
	  ; length of the intialized string
	  mov edx, helloLen
	  
	  ; interrupt to make linux syscall  
	  int 0x80  
	  
	  ; syscall for sys_exit
	  mov eax, 0x1  
	  
	  ; exit status 0
	  xor ebx, ebx
	  
	  ; interrupt to make syscall  
	  int 0x80
	  ;
	  ; this intruction is used to trigger and interrupt and allows you to invoke a system call from 
	  ; user space to kernel space. Basically we are requesting the OS for services.
	  ; This stops the processing and switches into kernel mode (ring0).
	  ;
;
; this section contains the actual program code. It starts with the _start label as the entrypoint
; and makes multiple sys_calls. It then exits the program with an interrupt.
;
```

---

# Compiling Assembly Code

Now that we have written the program, we need to compile it. To compile it you will need NASM. You can see installation instructions on how to install NASM [here](https://www.nasm.us/). Assembly code needs to be compiled, and then linked to the correct format, save the above code into `hello.asm` and follow the below steps:

```bash
salty@Loki:/tmp/asm_stuff$ nasm -f elf32 -o hello.o hello.asm
salty@Loki:/tmp/asm_stuff$ ld -m elf_i386 -o hello hello.o
salty@Loki:/tmp/asm_stuff$ ./hello
Hello world!
salty@Loki:/tmp/asm_stuff$
```
Let’s breakdown what we just did starting with `nasm -f elf32 -o hello.o hello.asm`:
```
nasm         # the program to run like running any linux program
-f elf32     # -f format, in this case we are compiling it into a 32bit ELF file
-o hello.o   # -o is the output file we want to use, by default it will be compiled to a.out if it is not passed
hello.asm    # now we take the keyword argument that is the name of the assembly file we want to compile
```
There are plenty of other formats you can compile into. By running `nasm -hf` you can see all of them. The next command is `ld -m elf_i386 -o hello hello.o`. Same thing, lets break it down:
```
ld           # same concept as above, just like running any other linux command
-m elf_i386  # -m EMULATION this allows us to set the emulation, meaning it is linked 32bit system calls
-o hello     # -o FILE specify the ouput filename
hello.o      # the keyword argument specifies that input filename to link
```
Once all these are done you will be able to call your output file by running it like so: `./hello`. This means that you have now successfully compiled and run an assembly program. 

---

#### Sponsor

Special thanks to the sponsor of this course: [TorGuard](https://torguard.net/)!

<p align="center">
    <img href="https://torguard.net/" src="../.github/sponsor_images/TG_Netflow_Ad_300_250.gif">
</p>

Surf safely [now](https://torguard.net/)

---

# In Closing
That's all there is to it! Assembly code can be daunting at times but is pretty simple once you get the grasp of it. In this course we have gone through the stack, the registers, building a simple program, and compiling that program successfully. We hope that this course has been useful to you and that you have learned something from it. Once again:

#### Support the Bible

Once again, this course is offered for free by The Perkins Cybersecurity Educational Fund in collaboration with Malcore! If you found this information valuable and want to support the continued development of the Malware Bible please consider:
- Donating to the Malware Bible Fund → [Donate Here](https://donorbox.org/malware-bible-fund)
- Registering for Malcore → [Sign Up](https://m4lc.io/courses/register)
- Joining the Malcore Discord → [Join Today](https://m4lc.io/courses/discord) 
- Exploring our incredible sponsor [Maldev Acadmeny](https://maldevacademy.com/)!

#### Become a sponsor

These courses reach thousands of cybersecurity professionals, researchers, students, and teachers worldwide who actively engage in learning and advancing the field. Sponsoring our educational initiative not only supports free cybersecurity education but also places your brand in front of a highly technical and security-conscious audience.

Interested in partnering? Let's talk about how your organization can be featured in our future courses: [Contact us today!](https://perkinsfund.org/) Please view our [Sponsorship Packages](../.github/sponsorships/sponsorship_package.md) for more details!
