# THIS IS A WORK IN PROGRESS AND IS NOT PUBLICLY RELEASED

<p align="center">
    <img src="">
</p>

##### Shameless plug

This cheatsheet is given to you for free by the Malcore team: LINK

Consider registering, and using Malcore, so we can continue to provide free content for the entire community. You can
also join our Discord server here: LINK

We offer free threat intel in our Discord via our custom designed Discord bot. Join the Discord to discuss this course
in further detail or to ask questions.

You can also support us by buying us a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/malcoreio)

# Windows PE Structure

The Windows Portable Executable (PE) file format is a structure used by Windows binary files. It is derived from the Common Object File Format (COFF) used in Unix systems, it is fundamental for Windows systems.

In this course we will break down the Windows PE structure thoroughly. 

## What is a DOS Header?

The purpose of the DOS header is to maintain backwards compatibility with older systems. It is a remnant of the DOS era, and tells the system that this is an executable in DOS while providing a pointer to the PE header where modern executable information starts.

### PE Structure

#### Structure Visualization

```shell
 ───────────────────────────────────────────────────────────────────
 00000000: 4d5a 9000 0300 0000 0400 0000 ffff 0000  MZ.............. ─┐ 
 00000010: b800 0000 0000 0000 4000 0000 0000 0000  ........@.......  │── DOS Header
 00000020: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000030: 0000 0000 0000 0000 0000 0000 f000 0000  ................ ─┘ 
 ───────────────────────────────────────────────────────────────────
 ───────────────────────────────────────────────────────────────────
 00000040: 0e1f ba0e 00b4 09cd 21b8 014c cd21 5468  ........!..L.!Th ─┐
 00000050: 6973 2070 726f 6772 616d 2063 616e 6e6f  is program canno  │─ DOS Stub
 00000060: 7420 6265 2072 756e 2069 6e20 444f 5320  t be run in DOS   │
 00000070: 6d6f 6465 2e0d 0d0a 2400 0000 0000 0000  mode....$....... ─┘
 ───────────────────────────────────────────────────────────────────
 ───────────────────────────────────────────────────────────────────
 000000f0: 5045 0000 4c01 0500 b1c6 a062 0000 0000  PE..L......b.... ─┐
 00000100: 0000 0000 e000 0201 0b01 0e1d 0010 0000  ................  │
 00000110: 0016 0000 0000 0000 e613 0000 0010 0000  ................  │
 00000120: 0020 0000 0000 4000 0010 0000 0002 0000  . ....@.........  │
 00000130: 0600 0000 0000 0000 0600 0000 0000 0000  ................  │
 00000140: 0060 0000 0004 0000 0000 0000 0300 4081  .`............@.  │
 00000150: 0000 1000 0010 0000 0000 1000 0010 0000  ................  │─ PE Header
 00000160: 0000 0000 1000 0000 0000 0000 0000 0000  ................  │
 00000170: 8c26 0000 a000 0000 0040 0000 e001 0000  .&.......@......  │
 00000180: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 00000190: 0050 0000 7401 0000 e821 0000 7000 0000  .P..t....!..p...  │
 000001a0: 0000 0000 0000 0000 0000 0000 0000 0000  ................  │
 000001b0: 0000 0000 0000 0000 5822 0000 4000 0000  ........X"..@...  │
 000001c0: 0000 0000 0000 0000 0020 0000 c800 0000  ......... ......  │
 000001d0: 0000 0000 0000 0000 0000 0000 0000 0000  ................ ─┘
 ───────────────────────────────────────────────────────────────────
 ───────────────────────────────────────────────────────────────────
 000001e0: 0000 0000 0000 0000 2e74 6578 7400 0000  .........text... ─┐
 000001f0: 110e 0000 0010 0000 0010 0000 0004 0000  ................  │
 00000200: 0000 0000 0000 0000 0000 0000 2000 0060  ............ ..`  │
 00000210: 2e72 6461 7461 0000 340c 0000 0020 0000  .rdata..4.... ..  │
 00000220: 000e 0000 0014 0000 0000 0000 0000 0000  ................  │
 00000230: 0000 0000 4000 0040 2e64 6174 6100 0000  ....@..@.data...  │
 00000240: 8803 0000 0030 0000 0002 0000 0022 0000  .....0......."..  │
 00000250: 0000 0000 0000 0000 0000 0000 4000 00c0  ............@...  │───── Sections
 00000260: 2e72 7372 6300 0000 e001 0000 0040 0000  .rsrc........@..  │
 00000270: 0002 0000 0024 0000 0000 0000 0000 0000  .....$..........  │
 00000280: 0000 0000 4000 0040 2e72 656c 6f63 0000  ....@..@.reloc..  │
 00000290: 7401 0000 0050 0000 0002 0000 0026 0000  t....P.......&..  │
 000002a0: 0000 0000 0000 0000 0000 0000 4000 0042  ............@..B  │
 00000400: b878 3340 00c3 cccc cccc cccc cccc cccc  .x3@............  │
 00000410: b870 3340 00c3 cccc cccc cccc cccc cccc  .p3@............  │
 00000420: 558b ec83 e4f8 5156 8b75 086a 01ff 15bc  U.....QV.u.j....  │
 00000430: 2040 0083 c404 8d4d 0c51 6a00 5650 e8bd   @.....M.Qj.VP..  │
 00000440: ffff ffff 7004 ff30 ff15 b820 4000 83c4  ....p..0... @...  │
 00000450: 185e 8be5 5dc3 cccc cccc cccc cccc cccc  .^..]........... ─┘
 ──────────────────────────────────────────────────────────────────── 
```

#### Full breakdown

##### DOS Header
  - Offset: `0x0`
    - `e_magic`: The signature that the system recognizes as a valid DOS executable: 0x0000
    - `e_lfanew`: The pointer to the PE header location: 0x003C

![e_magic](../.github/winpe/header_1.png)
![e_lfanew](../.github/winpe/header_2.png)

##### DOS Stub
  - Offset: `0x0040`
    - Usually contains the message: `This program cannot be run in DOS mode.`

![DOS Stub](../.github/winpe/header_3.png)

##### PE Signature
  - Offset is specified by `e_lfanew` header.
    - For example if `e_lfanew` is 0x000080 the signature is at 0x80
  - The signature is always `\x50\x45\x00\x00` in ASCII: `PE\0\0`

![PE Signature](../.github/winpe/header_4.png)

##### COFF File Header
  - Offset is typically directly after the PE signature
  - Contains general metadata about the file

| Offset | Size (Bytes) | Field Name            | Description                                                                                     |
|--------|--------------|------------------------|-------------------------------------------------------------------------------------------------|
| 0x00   | 2            | **Machine**            | Indicates the architecture for which the file is intended.                                      |
| 0x02   | 2            | **NumberOfSections**   | The number of sections in the PE file, such as `.text`, `.data`, etc.                           |
| 0x04   | 4            | **TimeDateStamp**      | The timestamp indicating when the file was created or last modified, in UNIX epoch format.      |
| 0x08   | 4            | **PointerToSymbolTable** | The file offset to the symbol table, used mainly in object files (usually 0 in executables).    |
| 0x0C   | 4            | **NumberOfSymbols**    | The number of entries in the symbol table, used in debugging or object files.                   |
| 0x10   | 2            | **SizeOfOptionalHeader** | The size of the Optional Header that follows this COFF header.                                  |
| 0x12   | 2            | **Characteristics**    | Flags that indicate the attributes and characteristics of the file (e.g., executable, DLL).     |

1. Machine
- **Offset**: `0x00`
- **Description**: Indicates the target architecture of the executable.
- **Possible Values**:
  - `0x014C` – Intel 386 (x86).
  - `0x0200` – Intel Itanium.
  - `0x8664` – x64 (AMD64).
  - `0x01C0` – ARM.
  - `0x01C4` – ARMv7.
  - `0xAA64` – ARM64.
  - `0x0100` – MIPS R3000.

![PE Signature](../.github/winpe/header_5.png)

2. Number of Sections
- **Offset**: `0x02`
- **Description**: The number of section headers in the PE file. This field tells the Windows loader how many sections to expect following the Optional Header.

![PE Signature](../.github/winpe/header_6.png)

3. Timestamp
- **Offset**: `0x04`
- **Description**: Contains the timestamp for when the file was created or last modified, expressed in UNIX epoch format (seconds since January 1, 1970).
- **Usage**: This can be used to analyze when a PE file was compiled or built.

![PE Signature](../.github/winpe/header_7.png)

4. PointerToSymbolTable
- **Offset**: `0x08`
- **Description**: Points to the start of the symbol table in the file, used mainly in object files (not in executables).
  - In executables and DLLs, this field is typically set to `0x00000000`.

![PE Signature](../.github/winpe/header_8.png)

5. Number of Symbols
- **Offset**: `0x0C`
- **Description**: The number of entries in the symbol table. This is used in object files for debugging purposes, but in executables, it’s generally set to `0x00000000`.

![PE Signature](../.github/winpe/header_9.png)

6. SizeOfOptionalHeader
- **Offset**: `0x10`
- **Description**: Specifies the size of the Optional Header that follows the COFF header.
  - For PE32 (32-bit) files, the size is usually `0x00E0` (224 bytes).
  - For PE32+ (64-bit) files, the size is typically `0x00F0` (240 bytes).

![PE Signature](../.github/winpe/header_10.png)

7. Characteristics
- **Offset**: `0x12`
- **Description**: Contains flags that describe the attributes of the PE file, like whether it's executable, relocatable, a DLL, etc.
- **Possible Values (Bit Flags)**:
  - `0x0002` – Executable image.
  - `0x0020` – Application can handle addresses larger than 2GB (large address aware).
  - `0x0100` – The file is a DLL.
  - `0x2000` – The file is a system file.
  - `0x4000` – File is a dynamically loadable driver.
  - `0x8000` – File is removable media-aware.

![PE Signature](../.github/winpe/header_11.png)
