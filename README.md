# 8086 Microprocessor-Based System

## Overview
This project presents the design of a complete microprocessor-based system built around the Intel 8086 architecture.

The system integrates memory, input/output interfaces, and display components, simulating a functional embedded system.

## Architecture
The system includes:
- Intel 8086 microprocessor (minimum mode)
- Clock generator (8284)
- Memory modules:
  - 128 KB EPROM
  - 64 KB SRAM
- I/O interfaces:
  - Serial communication (8251)
  - Parallel communication (8255)

## Peripherals
- 7-segment displays (8 digits)
- LCD display (2x16)
- LED indicators
- Matrix keyboard

## Functionality
The system allows:
- memory access and decoding
- communication via serial and parallel interfaces
- display control (LED, 7-segment, LCD)
- keyboard input handling

## Documentation
Full details (schematics, address decoding, routines) are available in the documentation file:
- `docs/DocumentatieBudaMaria.pdf`

## Notes
This project focuses on low-level system design and hardware-software interaction rather than high-level applications.
