# 4-to-1 Multiplexer using Verilog HDL

## 📌 Project Overview

This project implements a **4-to-1 Multiplexer (MUX)** using Verilog HDL. The design is implemented using different Verilog modeling techniques to understand how the same digital circuit can be described in multiple ways.

## 🔧 Modeling Techniques

- Behavioral Modeling
- Data Flow Modeling
- Gate-Level Modeling

## ⚙️ Inputs and Outputs

| Signal | Description |
|--------|-------------|
| I0-I3 | Four data inputs |
| S1, S0 | Select lines |
| Y | Output |

### Truth Table

| S1 | S0 | Output |
|----|----|--------|
| 0  | 0  | I0 |
| 0  | 1  | I1 |
| 1  | 0  | I2 |
| 1  | 1  | I3 |

## 📐 Circuit Diagram

### 4-to-1 MUX
<!-- Add your circuit diagram here -->
![4-to-1 MUX Circuit](images/mux_circuit.png)

## 💻 Verilog Code

### Behavioral Modeling

<img width="1224" height="690" alt="WhatsApp Image 2026-06-09 at 11 28 26 AM" src="https://github.com/user-attachments/assets/1041113d-b0d0-48c9-9d7b-6023f80ac087" />

### Data Flow Modeling
<img width="1221" height="680" alt="WhatsApp Image 2026-06-09 at 11 28 26 AM (4)" src="https://github.com/user-attachments/assets/c9a75340-be37-45a1-8821-e82cf722923d" />


### Gate-Level Modeling
<img width="1216" height="683" alt="WhatsApp Image 2026-06-09 at 11 28 26 AM (2)" src="https://github.com/user-attachments/assets/a4c9ed1d-cac5-49cb-81c6-3fb89a3656b5" />



## 📊 Simulation / Waveform
<img width="1214" height="720" alt="WhatsApp Image 2026-06-09 at 11 28 26 AM (3)" src="https://github.com/user-attachments/assets/669dac51-a497-4f8d-8a35-2efe12f0bd9f" />


## 🛠️ Tools Used

- Verilog HDL
- Vivado

## 🎯 Learning Outcome

This project demonstrates the implementation of a **4-to-1 Multiplexer** using different Verilog modeling techniques and provides practical understanding of **combinational logic and RTL design**.

