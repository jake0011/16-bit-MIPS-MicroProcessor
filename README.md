# MICROPROCESSOR DESIGN: MIPS IMPLEMENTATION

A 16-bit CPU implementation based on the MIPS Instruction Set Architecture (ISA).

This project is a simple implementation of a MIPS CPU, created and submitted as part of a course project. Its purpose was to test students' understanding of microprocessor architecture, including instruction set design, control logic, and data path implementation.

---

### Project Overview

This 16-bit MIPS CPU is designed to execute a range of basic arithmetic and logical operations, along with immediate instructions, jump, and branch functionalities. It provides a practical demonstration of a streamlined CPU model based on the MIPS ISA, emphasizing core instruction types and their execution within a basic microprocessor.

### Supported Operations

The CPU can perform the following operations:

- **Logical Operations:**
  - `AND`: Perform a bitwise AND operation between two registers.
  - `OR`: Perform a bitwise OR operation between two registers.
  - `XOR`: Perform a bitwise XOR operation between two registers.
  - `NOR`: Perform a bitwise NOR operation between two registers.

- **Arithmetic Operations:**
  - `ADD`: Add two register values and store the result in a destination register.
  - `SUB`: Subtract one register value from another and store the result in a destination register.
  - `SLT (Set Less Than)`: Set the destination register to 1 if the first register is less than the second, otherwise set it to 0.

### Additional Capabilities

In addition to the basic operations, this CPU implementation also supports:

- **Immediate Instructions:** These allow arithmetic and logical operations to be performed with an immediate (constant) value rather than another register.
  
- **Jump and Branch Operations:** These control instructions enable the CPU to:
  - Jump to a specific instruction address.
  - Branch to a new address based on a comparison result, allowing for conditional execution.

### Project Goals

The main objectives of this project were to:

1. Develop a simplified MIPS-based CPU model that could execute core operations.
2. Demonstrate an understanding of CPU control flow, including branching and jumping mechanisms.
3. Implement a minimal yet functional CPU capable of handling both basic arithmetic and logical tasks as well as conditional operations.

This MIPS CPU serves as an educational tool, offering a hands-on approach to understanding CPU architecture and instruction set implementation.
