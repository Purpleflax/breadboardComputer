# Breadboard-based 8-bit Computer (SAP-1)

A custom-built, breadboard-based 8-bit computer inspired by the SAP-1 (Simple As Possible) architecture and following [Ben Eater's video series](https://eater.net/8bit). This project demonstrates a fundamental understanding of computer architecture and showcases skills in digital electronics and circuit design.

![Breadboard-based 8-bit computer](breadboard_computer.jpg)

## Table of Contents

1. [Introduction](#introduction)
2. [Components](#components)
3. [SAP-1 Architecture](#sap1-architecture)
4. [Assembly and Building](#assembly-and-building)
5. [Programming](#programming)
6. [Future Improvements](#future-improvements)
7. [Conclusion](#conclusion)

## Introduction

The goal of this project is to build an 8-bit computer on a breadboard, using basic electronic components, following the SAP-1 architecture. This computer is capable of performing simple arithmetic and logical operations, as well as branching operations. It can execute custom assembly programs stored in its memory.

## Components

The key components used in this project include:

- Breadboards (multiple)
- 8-bit Microprocessor (e.g., 6502 or Z80)
- EEPROM (Electrically Erasable Programmable Read-Only Memory)
- RAM (Random Access Memory)
- Clock module
- 7-segment LED display
- Logic gates (AND, OR, NOT, XOR, etc.)
- 8-bit registers (e.g., 74LS173)
- 8-bit ALU (Arithmetic Logic Unit, e.g., 74LS181)
- Binary counter (e.g., 74LS161)
- Multiplexers (e.g., 74LS157)

## SAP-1 Architecture

The SAP-1 (Simple As Possible) architecture is a minimalistic 8-bit computer architecture that includes the following key elements:

- ALU (Arithmetic Logic Unit)
- Control Unit
- Registers (A, B, and Output)
- Memory Unit
- Clock
- Instruction Register
- Program Counter
- Input/Output Devices

![SAP-1 Architecture](sap1_architecture.jpg)

## Assembly and Building

The construction of this 8-bit computer is carried out step by step, following the [Ben Eater's video series](https://eater.net/8bit). The build process is organized into several modules, which are assembled and tested individually before integrating them into the complete computer system.

1. Clock module
2. Register module
3. ALU module
4. Memory module
5. Instruction Register module
6. Program Counter module
7. Control Unit module
8. Input/Output module

After completing the individual modules, they are connected to form the final computer.

## Programming

This 8-bit computer can be programmed using a custom assembly language that is converted to machine code and loaded into the EEPROM. Example programs include:

1. Adding two numbers
2. Subtracting two numbers
3. Bit manipulation
4. Displaying values on the 7-segment LED display
5. Implementing loops and branching operations

## Future Improvements

Potential improvements and expansions for this project:

1. Adding more memory to increase program capacity
2. Implementing interrupts and multitasking
3. Expanding the custom assembly language
4. Incorporating input devices (e.g., keyboard, mouse)
5. Developing a custom operating system
6. Designing custom hardware components

## Conclusion

This breadboard-based 8-bit computer project showcases a solid understanding of computer architecture and digital electronics. By following the SAP-1 architecture and Ben Eater's video
