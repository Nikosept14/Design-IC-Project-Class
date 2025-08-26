# Design-IC-Project-Class
# Full Adder Design (28 Transistors)

This repository contains the design and implementation of a **Full Adder** circuit as part of the *Semiconductor Devices and Integrated Circuits* course project at Institut Teknologi Sepuluh Nopember (ITS), Surabaya (2023).

A Full Adder is a fundamental digital circuit used for binary addition. In this project, the circuit is implemented using **28 transistors**, designed with **Xschem** and **Magic VLSI** tools. The Full Adder has three inputs (A, B, Cin) and two outputs (Sum, Cout).

---

## 🔹 Key Features
- **Logic Implementation** using 28 transistors.  
- **Schematic Design** with [Xschem](https://xschem.sourceforge.io/stefan/).  
- **Layout Design** using [Magic VLSI](http://opencircuitdesign.com/magic/).  
- **Functional Blocks**:
  - PMOS and NMOS implementations of AND and OR gates.  
  - Inverter stage for logic inversion.  
  - Combined XOR and AND logic for full adder functionality.  

---

## 🔹 Project Structure
-schematics/ → Xschem schematic files (AND, OR, XOR, inverter, full adder)
-layouts/ → Layout design using Magic VLSI
-simulation/ → Simulation results and waveform captures
-docs/ → Project report and documentation
---

## 🔹 Circuit Overview
- **Inputs:** A, B, Carry In (Cin)  
- **Outputs:** Sum, Carry Out (Cout)  
- **Transistors used:** 28 (PMOS + NMOS)

Truth Table:

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |

---

## 🔹 Layout Design
The project also includes a layout designed in Magic VLSI (see `layouts/` folder).  
This layout demonstrates the transistor-level implementation of the Full Adder.

---

## 🔹 Team Members
- **Niko Septian Kresno Nugroho** (5022211020)  
- **Farsya Ra'isah Fadhilia** (5022211096)  
- **Aqila Rashida** (5022211114)  

---

## 🔹 License
This project is for educational purposes only.  
Feel free to reference or adapt it for your own digital design projects.
