# FIFO Design in Verilog

## 📌 Overview
This project implements a **First-In-First-Out (FIFO) memory** in Verilog along with a **testbench** for simulation.  
The FIFO is designed to store 16 bytes (8-bit data each) and supports **write**, **read**, **full**, and **empty** functionality.  
The design follows **synchronous operation** with a positive-edge clock.

---

## 🛠 Features
- **16x8-bit FIFO Memory** (16 slots, each 8 bits wide)
- **Full & Empty flag generation**
- **Synchronous read & write operations**
- **Reset functionality to clear FIFO**
- **Testbench with reusable tasks** for:
  - Reset
  - Write data
  - Read data
  - Initialize read/write control signals
  - Waveform generation

---
