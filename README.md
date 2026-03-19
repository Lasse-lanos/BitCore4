# BitCore4

## Overview

BitCore4 is a 4-bit educational CPU designed in Logisim-Evolution. This project includes the CPU schematic, documentation of the architecture, instruction set, an assembler, example programs, and PCB design files. The goal of BitCore4 is to provide a clear, hands-on demonstration of basic CPU concepts and digital logic design. Please have in Mind that BitCore4 is still in development and not all features and documentation will be available at all times.

## Repository Structure

```
BitCore4/

│

├─ logisim/

│   cpu.circ          \# Main CPU schematic in Logisim

│

├─ docs/

│   architecture.md   \# Description of CPU architecture and components


├─ assembler/        \# Assembler (in development)

│

├─ programs/

│   hello.asm         \# Example assembly programs for BitCore4

│

├─ pcb/

│   gerber/           \# PCB design files for BitCore4

│

└─ README.md
```

## Architecture

The CPU is a 4-bit processor with the following components:

- **ALU** – Performs arithmetic and logical operations.

- **Registers** – Stores temporary data and instruction values.

- **Program Counter (PC)** – Tracks the address of the next instruction.

- **Instruction Decoder** – Decodes instructions from memory.

- **Control Logic** – Directs data flow and execution.

- **RAM / VRAM** – Supports 4-bit memory operations.

- **Bus System** – Handles communication between components.

For full details, see `docs/architecture.md`.

## Instruction Set

All instructions supported by BitCore4 are described in `docs/instruction\_set.md`. This includes opcodes, usage, and examples.

## Programming BitCore4

Example programs can be found in the `programs/` folder. These are written in BitCore4 assembly and can be assembled using the assembler (when available).

### Example

```
LOAD 4

ADD f, 1 

JMP f
```

## PCB and Hardware

PCB design files, including Gerber files, are located in the `pcb/gerber/` folder. These are intended for future hardware implementation of BitCore4.

## Contribution

Contributions are welcome. You can help by:

- Improving the Logisim schematic

- Adding example programs

- Developing the assembler

- Extending documentation

