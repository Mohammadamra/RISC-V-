# RISC-V Computer Organization

This repository contains materials, labs, and projects for learning **Computer Organization** using the open-source **RISC-V instruction set architecture (ISA)**.  
It serves as both a **learning resource** and a **hands-on guide** to understanding the inner workings of a processor, from basic instruction execution to pipelined CPU design.

---

## Overview

The RISC-V ISA is a modern, open, and extensible instruction set that has become the **de facto standard** for research and education.  
Through this repo, you’ll learn:

- Fundamentals of **Computer Organization and Design**
- How **RISC-V instructions** are structured and executed
- How to build a **single-cycle CPU**
- How to extend it into a **multi-cycle** and **pipelined CPU**
- Hazard detection, forwarding, and control handling
- Memory access, load/store operations, and I/O


---

## Topics Covered

1. **RISC-V ISA Basics**
   - Instruction formats (R, I, S, B, U, J types)
   - Registers and memory model
   - Arithmetic, logic, branch, and load/store instructions


2. **CPU Design**
   - Single-cycle datapath and control
   - Multi-cycle control using FSMs
   - Pipelining and performance metrics

3. **Hazards & Solutions**
   - Structural hazards
   - Data hazards (forwarding, stalling)
   - Control hazards (branch prediction)

4. **Memory & I/O**
   - Load/store mechanisms
   - Simple I/O-mapped memory examples

---

## How to Use

### Prerequisites
- **Verilog/SystemVerilog simulator** (Icarus Verilog, ModelSim, or equivalent)
- Python (optional, for automated testing scripts)
