# Uncommon Assembly Bugs: Memory Access Violations and Stack Corruption

This repository contains examples of uncommon assembly code errors, specifically focusing on memory access violations and stack overflows.  These errors are often subtle and difficult to debug.

## Bugs:

* **Memory Access Violations:** These occur when the program tries to access memory it doesn't have permission to access or memory that doesn't exist.  The examples demonstrate how incorrect addressing modes can lead to these violations.
* **Stack Overflows:** These happen when a program tries to write to the stack beyond its allocated space. The example shows how accessing the top of the stack directly can be very dangerous.

## Solutions:

The solutions provide corrected versions of the code that avoid these errors.  The solutions emphasize proper memory management and safe stack handling. 

## How to Use:

1. Clone this repository.
2. Assemble and link the code using your preferred assembler and linker (e.g., NASM and LD).
3. Run the code to observe the behavior of the buggy and corrected versions.

This project is intended for educational purposes to illustrate these rare but problematic errors that often crop up in low-level programming.