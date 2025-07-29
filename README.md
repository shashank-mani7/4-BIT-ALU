# 4-BIT-ALU
# 4-Bit ALU (Arithmetic Logic Unit) - Verilog Implementation

This project implements a **4-bit ALU (Arithmetic Logic Unit)** using Verilog. The ALU supports various arithmetic and logical operations such as addition, subtraction, AND, OR, XOR, and comparison. It is tested using a Verilog testbench and can be simulated in tools like ModelSim or Icarus Verilog.

---

## ⚙️ Features

- Supports 4-bit inputs `A` and `B`
- Output is 4-bit `Result` with `Zero`, `Carry`, and `Overflow` flags
- Operations include:
  - `000`: Addition
  - `001`: Subtraction
  - `010`: Bitwise AND
  - `011`: Bitwise OR
  - `100`: Bitwise XOR
  - `101`: Set-on-less-than (A < B)
  - `110`: Increment A
  - `111`: Decrement B

---

## 📂 Project Structure

```plaintext
4bit-alu-verilog/
├── alu.v             # ALU module
├── alu_tb.v          # Testbench module
├── waveform.png      # Optional waveform image
└── README.md         # Project documentation
