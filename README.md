# Nand_to_Tetris

> Building a modern computer from first principles — from a single NAND gate to a working computer, assembler, compiler and operating system.

![Status](https://img.shields.io/badge/status-in_progress-yellow) ![Progress](https://img.shields.io/badge/progress-1_of_12_projects-blue) ![Course](https://img.shields.io/badge/course-Nand2Tetris-purple)

This is my version of the 2-part project course (17 modules and 12 projects), which is to eventually build "Hack", a complete 16-bit computer system, one layer at a time.

---

## Why I'm building this

Way back I took a course called "Introduction to Computer Science" which introduced a version of Little man Computer (LMC), however, it neither delved into the spesifics nor did it show the whole picture in relation to other parts of the computer. Later on I stumbled upon this course, but the old Java software was prone to crashes when working on logic gates. Happily,  there's now a browser-based IDE to do the simulation.  So, now I'm finally filling in the missing threads.

## What I learned

- How simple logic gates work and to combine them to perform something else.

<!-- Keep 3–5 bullets; -->

## Projects

**🚧 Currently on: Project 1 (Boolean logic)** 

| # | Project | What it builds | Status |
|---|---------|----------------|--------|
| 01 | Boolean Logic | 15 basic logic gates from NAND | 🚧 In progress |
| 02 | Boolean Arithmetic | Half/full adders, 16-bit ALU | ⬜ Not started |
| 03 | Memory | Registers, counters, RAM chips | ⬜ Not started |
| 04 | Machine Language | Assembly programs for Hack | ⬜ Not started |
| 05 | Computer Architecture | Full CPU + memory | ⬜ Not started |
| 06 | Assembler | Hack assembler in Python | ⬜ Not started |
| 07–08 | Virtual Machine I–II | Stack-based VM translator | ⬜ Not started |
| 09 | High-Level Language | Program written in Jack | ⬜ Not started |
| 10–11 | Compiler I–II | Jack → VM compiler | ⬜ Not started |
| 12 | Operating System | Mini OS library in Jack | ⬜ Not started |

Part 1 covers projects 1–6 (the hardware platform, ending with the assembler) and part 2 covers projects 7–12 (the software hierarchy with VM, compiler and OS).

Part 1 - https://www.coursera.org/learn/build-a-computer
Part 2 - https://www.coursera.org/learn/nand2tetris2

<!-- Placeholder: ✅ Done ; 🚧 In progress ; ⬜ Not started -->

## Tools & setup

Each project lives in `projects/<>/`.  logic gates Chips are written in HDL and tested with the online Nand2Tetris Hardware Simulator; later projects use the supplied test scripts (`.tst`) and compare against expected output (`.cmp`).

Notepad++, VScodium, online IDE

<!--Lang for software projects further in: **Python** or C/etc. -->


## Highlights

---

## Attribution & license

Implementation code in this repo is released under the MIT License. All chip/program implementations are my own. Course materials remain © the authors.
