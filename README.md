# COE328-Lab6-CPU-Design  

**Note: Source Code not included to preserve academic integrity.**

---

## Overview  
This project is a digital logic design lab completed individually as part of COE 328: Digital Systems at Toronto Metropolitan University. The lab focuses on designing and testing key components of a simplified CPU unit on an FPGA board, including FSMs, decoders, registers, and ALUs. The design was developed using Quartus Prime with a focus on hardware simulation, waveform analysis, and modular logic design.

---

## Objectives  
- Design and implement basic components of a CPU using hardware description concepts  
- Understand and simulate the behavior of FSMs and opcode-based ALU control  
- Display computed results on a 7-segment display via BCD decoding  
- Analyze waveforms to validate logical behavior of each component  

---

## Features  

### Components  
- **Register A & B**: 8-bit latch storage, used for input to ALU  
- **Finite State Machine (FSM)**: Controls state transitions and produces 4-bit opcode outputs  
- **4:16 Decoder**: Decodes 4-bit state into a 16-bit opcode for ALU control  
- **ALU Core**: Performs operations like addition, inversion, OR, XNOR, swap, and compare based on opcodes  
- **BCD Decoder**: Converts binary output to 7-segment display format  

### Lab Problem Sets  
- **ALU_1**: Performs standard ALU operations (add, subtract, etc.) using opcode control  
- **ALU_2**: Implements custom operations like bit inversion, swap, and point-based logic  
- **ALU_3**: Takes student number as input and checks even/odd status for display  

---

## Tools and Technologies  
- **Language/Platform**: Quartus Prime (Verilog/VHDL concepts)  
- **Simulation**: Waveform timing analysis  
- **Design/Modeling**: Block diagrams, state machines, truth tables  
- **Hardware**: FPGA board (e.g., DE1-SoC or similar)  

---

## My Role  
- **Full project developed individually**  
- Designed and tested each digital component from scratch  
- Generated and analyzed waveforms for functional verification  
- Wrote and formatted final lab report, including all schematics, microcode, truth tables, and results  
- Integrated student ID into FSM-based opcode control logic for personalized output behavior  

---

## Disclaimer  
This project was completed as part of a university course and is subject to academic integrity policies. Code and Quartus files have been withheld to prevent reuse. This repository is for portfolio demonstration only.
