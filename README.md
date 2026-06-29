# FPGA-Based-Digital-Clock-Design
This project implements a 24-hour Digital Clock (HH:MM:SS) using Verilog HDL and simulates the design on a laptop without requiring physical FPGA hardware. The clock updates seconds, minutes, and hours using sequential logic and demonstrates concepts of digital design, counters, timing, and RTL simulation.
Overview

This project implements a 24-hour Digital Clock (HH:MM:SS) using Verilog HDL and simulates the design on a laptop without requiring physical FPGA hardware.

The clock updates seconds, minutes, and hours using sequential logic and demonstrates concepts of digital design, counters, timing, and RTL simulation.

---

Features

- 24-hour clock format
- Hours (00–23)
- Minutes (00–59)
- Seconds (00–59)
- Reset functionality
- Waveform generation

---

Project Architecture

Clock Input
↓
Clock Divider
↓
Second Counter
↓
Minute Counter
↓
Hour Counter
↓
Digital Display

---

Tools Used

- Verilog HDL
- EDA Playground
- Icarus Verilog
- EPWave (Waveform Viewer)


---

Project Structure

FPGA_Digital_Clock/



├── tb/
│ └── tb_clock.v

├── waveform/

└── README.md

---

How to Run

1. Open EDA Playground
2. Select Language → Verilog
3. Select Simulator → Icarus Verilog
4. Paste "digital_clock.v"
5. Paste "tb_clock.v"
6. Click Run
7. Open EPWave to view simulation waveform

---

Expected Output

Time = 0:0:1
Time = 0:0:2
Time = 0:0:3

...

Time = 0:1:0

---

Simulation Result

The clock increments:

- Seconds from 00–59
- Minutes after every 60 seconds
- Hours after every 60 minutes
- Resets to 00:00:00 after 23:59:59

---

Future Enhancements

- 12/24 Hour Mode
- Alarm Function
- Stopwatch
- Seven Segment Display
- FPGA Board Implementation
- Clock Divider Optimization

---

Learning Outcomes

- Verilog HDL Coding
- Sequential Logic Design
- Counter Design
- Testbench Development
- RTL Simulation
- Waveform Analysis

---

Author

Ismail Saji
Electronics and Communication Engineering
VLSI | Embedded Systems | Digital DesignAlso upload:

digital_clock.v

tb_clock.v

waveform screenshot
<img width="1887" height="600" alt="Screenshot 2026-06-21 205130" src="https://github.com/user-attachments/assets/8810f843-ecdb-4453-9eee-16c4b6d1f57f" />



