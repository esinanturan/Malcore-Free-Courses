# THIS IS A WORK IN PROGRESS AND IS NOT PUBLICLY RELEASED YET

<p align="center">
    <img src="">
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/) in collaboration with the Malcore team: [https://m4lc.io/courses/register](https://m4lc.io/courses/register)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund and registering for Malcore. You can also join the Malcore Discord server here: [https://m4lc.io/courses/discord](https://m4lc.io/courses/discord)

Malcore offers free threat intel in our Discord via their custom designed Discord bot. Join the Discord to discuss this course in further detail or to ask questions.

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)

---

# What will be covered?
- [What is an ELF file?](#what-is-an-elf-file)
- [Detailed breakdown](#breakdown-of-the-elf-file)
  - [Header](#elf-header)
  - [Program header](#program-header)
  - [Section header](#section-header)
- [ELF sections](#elf-sections)
  - [Section overview](#elf-file-sections-overview)
  - [Dynamic sections](#dynamic-sections)
  - [Relocation sections](#relocation-sections)
  - [Note section](#note-section)
  - [Core dump section](#core-dump-section)
- [Tables](#elf-file-tables)
  - [Symbol table](#symbol-table)
  - [String table](#string-table)
- [That's it](#in-closing)

# What is an ELF file?

The executable and linkable format (ELF) is a standard file format for executables, object code, shared libraries, and core dumps. ELF format is widely used on Unix based operating systems. It is designed to be flexible and extensible.

---

# Breakdown of the ELF file

To visualize the file format we have created a basic ascii representation of the file

```shell
───────────────────────────────────────────────────────────────────
 00000000: 7f45 4c46 0201 0100 0000 0000 0000 0000  .ELF............ ─┐
 00000010: 0200 3e00 0100 0000 0000 0000 0000 0000  ..>.............  │── ELF Header
 00000020: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000030: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 00000040: 0100 0000 0000 0000 4000 0000 0000 0000  ........@....... ─┐
 00000050: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │─ Program Header Table (PHT)
 00000060: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000070: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 00000080: 0100 0000 0000 0000 0000 0000 0000 0000  ................ ─┐
 00000090: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 000000A0: 2e74 6578 7400 0000 1200 0000 0100 0000  .text...........  │────── Sections
 000000B0: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 000000C0: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 000000D0: 2e64 6174 6100 0000 1200 0000 0000 0000  .data.......... ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 000000E0: 0300 0000 0000 0000 2e73 796d 7461 6200  .........symtab. ─┐
 000000F0: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │── Symbol Table
 00000100: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000110: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 00000120: 0300 0000 0000 0000 2e73 7472 7461 6200  .........strtab. ─┐
 00000130: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │── String Table
 00000140: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000150: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 00000160: 0400 0000 0000 0000 2e72 656c 6f63 2e64  .........reloc.d ─┐
 00000170: 6174 6100 0000 0000 0000 0000 0000 0000  ata.............. │── Relocation Section
 00000180: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000190: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
───────────────────────────────────────────────────────────────────
 000001A0: 0500 0000 0000 0000 2e6e 6f74 6500 0000  .........note... ─┐
 000001B0: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │── Note Section
 000001C0: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
───────────────────────────────────────────────────────────────────
```

### ELF header

The header is located at the beginning of the file:

![Header](../.github/elf/img.png)

Contained within this header are multiple pieces of information. This information provides essential data to tell the system what kind of ELf file this is.

- `e_ident`
  - Contains the magic number to identify the file as an ELF, also holds info on the class/architecture (32 or 64), encoding, and ELF version
    - 16 bytes long
      - Magic number (`7F 45 4C 46` -> `.ELF`)
      - Class (or architecture)
        - `0x02` == 64bit
        - `0x01` == 32bit
      - Data encoding
        - `0x01` == little endian
        - `0x02` == big endian
      - ELF version (usually `0x01`)
      - Padding bytes

![e_ident](../.github/elf/img_1.png)

- `e_type`
  - Specifies the file type, such as: relocatable, executable, shared object, or core.
  - Possible types:

| Bytes  | Description                   |
|--------|-------------------------------|
| `0x00` | 	System V                     |
| `0x01` | 	HP-UX                        |
| `0x02` | 	NetBSD                       |
| `0x03` | 	Linux                        |
| `0x04` | 	GNU Hurd                     |
| `0x06` | 	Solaris                      |
| `0x07` | 	AIX (Monterey)               |
| `0x08` | 	IRIX                         |
| `0x09` | 	FreeBSD                      |
| `0x0A` | 	Tru64                        |
| `0x0B` | 	Novell Modesto               |
| `0x0C` | 	OpenBSD                      |
| `0x0D` | 	OpenVMS                      |
| `0x0E` | 	NonStop Kernel               |
| `0x0F` | 	AROS                         |
| `0x10` | 	FenixOS                      |
| `0x11` | 	Nuxi CloudABI                |
| `0x12` | 	Stratus Technologies OpenVOS |

![e_type](../.github/elf/img_2.png)

- `e_machines`
  - Indicates what class/architecture the ELF files is
  - Most common types:

| `e_machine` Value | Constant       | Description                           |
|-------------------|----------------|---------------------------------------|
| `0x00`            | `EM_NONE`      | No machine                           |
| `0x02`            | `EM_M32`       | AT&T WE 32100                        |
| `0x03`            | `EM_SPARC`     | SPARC                                |
| `0x07`            | `EM_68K`       | Motorola 68000                       |
| `0x08`            | `EM_88K`       | Motorola 88000                       |
| `0x14`            | `EM_860`       | Intel 80860                          |
| `0x16`            | `EM_R3000`     | MIPS I Architecture (R3000)          |
| `0x28`            | `EM_ARM`       | ARM                                  |
| `0x2A`            | `EM_SUPERH`    | Hitachi SH                           |
| `0x32`            | `EM_IA_64`     | Intel Itanium                        |
| `0x3E`            | `EM_X86_64`    | AMD x86-64 (x64)                     |
| `0xB7`            | `EM_AARCH64`   | ARM 64-bit (AArch64)                 |
| `0xF3`            | `EM_RISCV`     | RISC-V                               |

  - Other notable types:

| `e_machine` Value | Constant         | Description                             |
|-------------------|------------------|-----------------------------------------|
| `0x13`            | `EM_386`         | Intel 80386                             |
| `0x15`            | `EM_PARISC`      | HP/PA RISC                              |
| `0x2B`            | `EM_ECOG2`       | Cyan Technology eCOG2                   |
| `0x42`            | `EM_ALPHA`       | DEC Alpha                               |
| `0x8C`            | `EM_AVR`         | Atmel AVR                               |
| `0xA2`            | `EM_MSP430`      | Texas Instruments MSP430                |
| `0xA3`            | `EM_BLACKFIN`    | Analog Devices Blackfin                 |
| `0xDC`            | `EM_TI_C6000`    | Texas Instruments TMS320C6000 DSP family|
| `0xF7`            | `EM_BPF`         | Berkeley Packet Filter                  |

![e_machine](../.github/elf/img_3.png)

- `e_version`
  - This indicates the version of ELF that is being used. There are really only two different version:
    - `0x00000000`
      - `EV_NONE`
        - Invalid version
    - `0x00000001`
      - `EV_CURRENT`
        - Current version (original version 1)

![e_version](../.github/elf/img_4.png)


### Program header

### Section header

---

# ELF sections

### ELF file sections overview

### Dynamic sections

### Relocation sections

### Note section

### Core dump section

---

# ELF file tables

### Symbol table

### String table

---

# In closing