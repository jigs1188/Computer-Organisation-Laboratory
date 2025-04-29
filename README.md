
# Computer Organisation Laboratory

This repository contains a series of laboratory exercises designed to deepen understanding of computer organization, digital logic design, and processor architecture. The labs involve practical implementation of fundamental concepts like adders, multipliers, RISC-V pipelines, and more, using Verilog and other tools.

## Table of Contents
- [Introduction](#introduction)
- [Lab Descriptions](#lab-descriptions)
  - [Lab 1: Adder Topologies](#lab-1-adder-topologies)
  - [Lab 2: Adder/Subtractor Topologies](#lab-2-addersubtractor-topologies)
  - [Lab 3: Multiplier Topologies](#lab-3-multiplier-topologies)
  - [Lab 4: RISC-V Decoder and Register File](#lab-4-risc-v-decoder-and-register-file)
  - [Lab 6: Two-Stage RISC-V Pipeline](#lab-6-two-stage-risc-v-pipeline)
- [Setup and Usage](#setup-and-usage)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

---

## Introduction

The **Computer Organisation Laboratory** is aimed at providing hands-on experience with various components of computer architecture and digital design. Each lab is focused on solving specific problems to analyze the efficiency of different topologies and designs in terms of processing delay and power consumption.

---

## Lab Descriptions

### Lab 1: Adder Topologies
**Objective**: Analyze the efficiency of different adder topologies in terms of processing delay and power consumption.

**Tasks**:
- Implement addition for two 4-bit unsigned numbers (\(A\) and \(B\)) using:
  1. Four full adders and two 4-bit registers (R0 and R1).
  2. One full adder and two 4-bit registers (R0 and R1).
- Compare the scenarios in terms of processing delay and power consumption.

---

### Lab 2: Adder/Subtractor Topologies
**Objective**: Analyze the efficiency of different adder/subtractor topologies.

**Tasks**:
- Implement addition using carry generate and propagate logic.
- Implement subtraction using carry generate and propagate logic and ripple carry adder.
- Compare performance with Lab 1 scenarios in terms of processing delay and power consumption.

---

### Lab 3: Multiplier Topologies
**Objective**: Analyze the efficiency of multiplier topologies.

**Tasks**:
- Implement:
  1. An array multiplier for unsigned numbers.
  2. Booth’s algorithm for two’s complement numbers.
- Compare processing delay and power consumption.

---

### Lab 4: RISC-V Decoder and Register File
**Objective**: Design a RISC-V instruction decoder unit and register file unit.

**Tasks**:
- **Decoder Unit**:
  - Process 32-bit RISC-V instructions (R-type and I-type).
  - Output opcode, addresses of source registers, destination register, and immediate value.
- **Register File**:
  - 32 32-bit registers (x0 to x31).
  - Two read ports and one write port.

---

### Lab 6: Two-Stage RISC-V Pipeline
**Objective**: Design a two-stage RISC-V pipeline combining ALU and Register File.

**Tasks**:
- Process a sequence of 32-bit R-type and I-type instructions.
- Perform operations (addition, subtraction, multiplication) using an ALU.
- Use pipeline registers for intermediate data and control values.
- Identify sizes for each stage of pipeline registers.

---

## Setup and Usage

### Prerequisites
1. Install a Verilog simulator (e.g., ModelSim, Vivado, or Icarus Verilog).
2. Clone the repository:
   ```bash
   git clone https://github.com/jigs1188/Computer-Organisation-Laboratory.git
   ```
3. Navigate to the desired lab directory:
   ```bash
   cd Computer-Organisation-Laboratory
   ```

### Running the Code
1. Open the Verilog simulator.
2. Load the corresponding `.v` files for the lab you want to test.
3. Run the simulation to analyze results.

---

## Technologies Used
- **Languages**: Verilog
- **Tools**: RISC-V architecture, digital logic design concepts
- **Platform**: Linux, Windows, or macOS (for simulation tools)

---

## Contributors
- [jigs1188](https://github.com/jigs1188)

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

