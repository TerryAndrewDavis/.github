<div align="center">

# Terry A. Davis

### Programmer. Engineer. Creator of TempleOS.

`1969 - 2018`

![Born](https://img.shields.io/badge/Born-December%2015%2C%201969-0d1117?style=for-the-badge)
![Died](https://img.shields.io/badge/Died-August%2011%2C%202018-0d1117?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-HolyC-0d1117?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-TempleOS-0d1117?style=for-the-badge)

</div>

---

## Overview

Terry Allen Davis was an American electrical engineer and self-taught systems programmer who spent roughly a decade writing an entire operating system, compiler, and programming language by himself. The result was **TempleOS**, a 64-bit, 16-color, 640x480 operating system he described as a modern Commodore 64 and a temple to God.

He wrote the kernel, the compiler, the editor, the graphics library, the games, and the tools. Nobody else wrote a meaningful part of it.

---

## Quick Facts

| | |
|---|---|
| **Full name** | Terry Allen Davis |
| **Born** | December 15, 1969, West Allis, Wisconsin |
| **Died** | August 11, 2018, Portland, Oregon |
| **Education** | Electrical engineering, Arizona State University |
| **Profession** | Engineer and independent programmer |
| **Known for** | TempleOS, HolyC |
| **Language** | HolyC (his own dialect of C) |

---

## TempleOS

TempleOS began around 2003 and went through several names as it grew: **J Operating System**, **LoseThos**, **SparrowOS**, and finally **TempleOS** in 2013. It was developed and released as free, public domain software.

### Design choices

- **Ring-0 only.** Everything runs in kernel mode, with no privilege separation.
- **Single address space.** All code and data share one flat memory space.
- **64-bit, with identity-mapped memory.**
- **640x480, 16 colors.** A deliberate constraint he compared to a classic console.
- **No networking.** It was meant to be a self-contained machine.
- **Compiler built into the shell.** The command line and the programming language are the same thing.
- **Source-level everything.** The entire system, from kernel to games, ships as readable source and can be edited live.

### What shipped with it

- A custom compiler and JIT for HolyC
- DolDoc, a hypertext document format that mixes text, sprites, and code
- A text editor, sprite editor, and 3D graphics routines
- Games and demos, all written by Terry
- An oracle program for generating random words, which he treated as a form of divination

The project totals on the order of 100,000 lines of code, written alone.

---

## HolyC

HolyC is the language Terry built for TempleOS. It resembles C and C++ but drops a lot of ceremony, and it is used both as the system language and as the shell scripting language.

```c
"Hello\n";

U0 Greet(U8 *name)
{
  "Hello, %s.\n", name;
}

Greet("Terry");
```

Notable traits:

- Bare strings in statement position are printed automatically
- Functions can be called without parentheses when they take no arguments
- Built-in types like `U0`, `U8`, `I64`, and `F64`
- Code runs straight from the command line through the JIT

---

## Timeline

| Year | Event |
|---|---|
| 1969 | Born in West Allis, Wisconsin |
| 1990s | Studies electrical engineering at Arizona State University |
| Mid 1990s | First serious mental health crisis; later diagnosed with schizophrenia |
| 2000s | Works as an engineer and begins writing his own operating system |
| 2003 | Early development of what becomes TempleOS |
| 2005 | Project is known as LoseThos |
| 2013 | Renamed SparrowOS, then TempleOS |
| 2017 | Continues active development and releases videos and demos |
| 2018 | Dies in Portland, Oregon, at age 48 |

---

## Legacy

Terry Davis lived with severe mental illness for most of his adult life, and much of his public story has been told through jokes and memes. The work itself deserves to be judged on its own terms. Programmers who study TempleOS often point to its coherence, its ambition, and the sheer skill required to build a complete computing environment alone.

His code is still read, run in virtual machines, ported, and studied, and his work continues to be a reference point in discussions about solo software craftsmanship.

---

## Run TempleOS Yourself

TempleOS runs well in a virtual machine.

1. Download the official ISO from [templeos.org](https://templeos.org)
2. Create a new 64-bit VM in VirtualBox or QEMU with no network adapter
3. Boot from the ISO and choose the installer, or run it live
4. Open the demos and games from the file browser

---

<div align="center">

*Terry A. Davis, December 15, 1969 - August 11, 2018*

</div>
