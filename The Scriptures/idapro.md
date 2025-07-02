<p align="center">
    <img src="../.github/idapro-cheatsheet.png">
</p>

**Shameless plug**

This course is given to you for free by The Perkins Cybersecurity Educational Fund: [https://perkinsfund.org/](https://perkinsfund.org/)

Please consider donating to [The Perkins Cybersecurity Educational](https://donorbox.org/malware-bible-fund) Fund 

You can also support The Perkins Cybersecurity Educational Fund by buying them a coffee

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/perkinsfund)**

---

## Index

- [Keys](#keys)
- [Navigation](#navigation)
- [Search](#search)
- [Graphing](#graphing)
- [Comments](#comments)
- [Data Format Options](#data-format-options)
- [Open Subviews](#open-subviews)
- [File Operations](#file-operations)
- [Debugger](#debugger)
- [Breakpoints](#breakpoints)
- [Watches](#watches)
- [Tracing](#tracing)
- [Misc](#miscellaneous)
- [Edit](#edit-data-types--etc)
- [Operand Type](#operand-type)
- [Segments](#segments)
- [Structs](#structs)
- [Functions](#functions)

---

## Keys

| Image                                                               | Description |
|---------------------------------------------------------------------|-------------|
| <img src="../.github/keys/shift-key-48.png" height="20" width="20"> | Shift key   |
| <img src="../.github/keys/alt-key-48.png" height="20" width="20">   | Alt key     |
| <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">  | Control key |
| <img src="../.github/keys/esc-key-48.png" height="20" width="20">   | Escape key  |
| <img src="../.github/keys/enter-key-48.png" height="20" width="20"> | Enter key   |

---

## Navigation

| Action                    | Shortcut                                                                                                                               |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Jump to operand           | <img src="../.github/keys/enter-key-48.png" height="20" width="20">                                                                    |
| Jump in new window        | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+<img src="../.github/keys/enter-key-48.png" height="20" width="20">  |
| Jump to previous position | <img src="../.github/keys/esc-key-48.png" height="20" width="20">                                                                      |
| Jump to Next position     | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+<img src="../.github/keys/enter-key-48.png" height="20" width="20"> |
| Jump to address           | G                                                                                                                                      |
| Jump by name              | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+L                                                                   |
| Jump to function          | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+P                                                                   |
| Jump to segment           | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+S                                                                   |
| Jump to segment register  | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+G                                                                   |
| Jump to problem           | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+Q                                                                   |
| Jump to cross reference   | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+X                                                                   |
| Jump to xref to operand   | X                                                                                                                                      |
| Jump to entry point       | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+E                                                                   |
| Mark Position             | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+M                                                                    |

---

## Search

| Action                 | Shortcut                                                             |
|------------------------|----------------------------------------------------------------------|
| Next code              | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+C  |
| Next data              | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+D |
| Next explored          | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+A |
| Next unexplored        | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+U |
| Immediate value        | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+I  |
| Next immediate value   | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+I |
| Text                   | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+T  |
| Next text              | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+T |
| Sequence of bytes      | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+B  |
| Next sequence of bytes | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+B |
| Not function           | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+U  |

---

## Graphing

| Action         | Shortcut                                                               |
|----------------|------------------------------------------------------------------------|
| Flow chart     | F12                                                                    |
| Function calls | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+F12 |

---

## Comments

| Action                    | Shortcut                                                                |
|---------------------------|-------------------------------------------------------------------------|
| Enter comment             | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+;   |
| Enter repeatable comment  | ;                                                                       |
| Enter anterior lines      | Ins                                                                     |
| Enter posterior lines     | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+Ins |
| Insert predefined comment | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F1  |

---

## Data Format Options

| Action              | Shortcut                                                            |
|---------------------|---------------------------------------------------------------------|
| ASCII strings style | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+A |
| Setup data types    | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+D |

---

## Open Subviews

| Action            | Shortcut                                                                |
|-------------------|-------------------------------------------------------------------------|
| Names             | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F4  |
| Functions         | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F3  |
| Strings           | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F12 |
| Segments          | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F7  |
| Segment registers | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F8  |
| Signatures        | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F5  |
| Type libraries    | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F11 |
| Structures        | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F9  |
| Enumerations      | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F10 |

---

## File Operations

| Action              | Shortcut                                                              |
|---------------------|-----------------------------------------------------------------------|
| Parse C header file | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+F9 |
| Create ASM file     | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+F10 |
| Save database       | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+W  |

---

## Debugger

| Action            | Shortcut                                                              |
|-------------------|-----------------------------------------------------------------------|
| Start process     | F9                                                                    |
| Terminate process | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+F2 |
| Step into         | F7                                                                    |
| Step over         | F8                                                                    |
| Run until return  | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+F7 |
| Run to cursor     | F4                                                                    |

---

## Breakpoints

| Action          | Shortcut                                                                                                                               |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Breakpoint list | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+<img src="../.github/keys/alt-key-48.png" height="20" width="20">+B |

---

## Watches

| Action       | Shortcut |
|--------------|----------|
| Delete watch | Del      |

---

## Tracing

| Action      | Shortcut                                                                                                                               |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Stack trace | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+<img src="../.github/keys/alt-key-48.png" height="20" width="20">+S |

---

## Miscellaneous

| Action                   | Shortcut                                                                  |
|--------------------------|---------------------------------------------------------------------------|
| Calculator               | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+/     |
| Cycle through open views | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+Tab    |
| Select tab               | <img src="../.github/keys/alt-key-48.png" height="20" width="20"> + [1…N] |
| Close current view       | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+F4     |
| Exit                     | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+X       |
| IDC Command              | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+F2    |

---

## Edit (Data Types – etc)

| Action             | Shortcut                                                               |
|--------------------|------------------------------------------------------------------------|
| Copy               | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+Ins |
| Begin selection    | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+L    |
| Manual instruction | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+F2   |
| Code               | C                                                                      |
| Data               | D                                                                      |
| Struct variable    | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+Q    |
| ASCII string       | A                                                                      |
| Array              | Num *                                                                  |
| Undefine           | U                                                                      |
| Rename             | N                                                                      |

---

## Operand Type

| Action                   | Shortcut                                                              |
|--------------------------|-----------------------------------------------------------------------|
| Offset (data segment)    | O                                                                     |
| Offset (current segment) | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+O  |
| Offset by (any segment)  | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+R   |
| Offset (user-defined)    | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+R  |
| Offset (struct)          | T                                                                     |
| Number (default)         | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+3 |
| Hexadecimal              | Q                                                                     |
| Decimal                  | H                                                                     |
| Binary                   | B                                                                     |
| Character                | R                                                                     |
| Segment                  | S                                                                     |
| Enum member              | M                                                                     |
| Stack variable           | K                                                                     |
| Change sign              | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+- |
| Bitwise negate           | <img src="../.github/keys/shift-key-48.png" height="20" width="20">+` |
| Manual                   | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+F1  |

---

## Segments

| Action                        | Shortcut                                                            |
|-------------------------------|---------------------------------------------------------------------|
| Edit segment                  | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+S |
| Change segment register value | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+G |

---

## Structs

| Action                  | Shortcut                                                             |
|-------------------------|----------------------------------------------------------------------|
| Struct var              | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+Q  |
| Force zero offset field | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+Z |
| Select union member     | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+Y  |

---

## Functions

| Action               | Shortcut                                                             |
|----------------------|----------------------------------------------------------------------|
| Create function      | P                                                                    |
| Edit function        | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+P  |
| Set function end     | E                                                                    |
| Stack variables      | <img src="../.github/keys/ctrl-key-48.png" height="20" width="20">+K |
| Change stack pointer | <img src="../.github/keys/alt-key-48.png" height="20" width="20">+K  |
| Rename register      | V                                                                    |
| Set function type    | Y                                                                    |


