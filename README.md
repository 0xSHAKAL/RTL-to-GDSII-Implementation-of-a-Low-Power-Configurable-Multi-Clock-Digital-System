# RTL-to-GDSII Implementation of a Low-Power Configurable Multi-Clock Digital System

<p align="center">
Complete ASIC Physical Design Flow using Cadence EDA tool on gpdk45 nm Technology
</p>

---

# Project Overview

This project presents the complete RTL-to-GDSII implementation of a Low-Power Configurable Multi-Clock Digital System using industry-standard ASIC design methodologies.

The design integrates multiple clock domains with low-power optimization techniques and demonstrates the complete physical implementation flow from RTL synthesis to final GDSII generation.

---

# Key Features

- Multi-Clock Digital Architecture
- Low Power Design
- Timing Driven Physical Design
- Complete RTL-to-GDSII Implementation
- gpdk45 nm Technology Node

---

# System Blocks

- ALU
- Register File
- Clock Divider
- Clock Gating
- Synchronizers
- FIFO
- UART RX
- UART TX
- Top Integration

---

# Design Flow

Logic Synthesis

↓

LEC (Logic Equivalence Checking)

↓

Floorplanning

↓

Power Planning

↓

Placement

↓

Clock Tree Synthesis (CTS)

↓

Routing

↓

Post Route Optimization

↓

Timing Closure

↓

GDSII Generation

---

# Technology & Tools

| Technology | SKY130 |
|----------------|----------------|
| HDL | Verilog |
| Synthesis | Cadence Genus |
| Physical Design | Cadence Innovus |
| Timing Analysis | Tempus |
| Output | GDSII |

---

# Physical Design Flow

## Floorplan

1:1 of aspect ratio with 40% of core utilization.

<img width="778" height="750" alt="floorplan" src="https://github.com/user-attachments/assets/13cfac15-9080-4223-9c38-24f3e92b8bf8" />

## Power Planning

Power rings, power stripes, and power rails are inserted for power planning to reduce the IR drop and minimize the effect of electromigration.

<img width="812" height="767" alt="Power Planning" src="https://github.com/user-attachments/assets/1fb33294-e685-420d-9e66-789236c4ea4b" />

## Placement

Placement of Standard Cells.

<img width="785" height="757" alt="std_cell_placement" src="https://github.com/user-attachments/assets/0881612f-348f-4372-9adb-88f08a6ca9df" />

## Clock Tree Synthesis

CTS was performed to build a clock tree structure.

<img width="775" height="750" alt="CTS" src="https://github.com/user-attachments/assets/27beaf27-e7d3-4cdd-a081-508f5bb355c7" />

## Routing

Routed the design to make connections between cells.

<img width="800" height="767" alt="Routing" src="https://github.com/user-attachments/assets/8a8d6c46-cced-41f1-8cbb-016340749bff" />

## Final Layout

Insert filler cells & generated GDSII file.

<img width="798" height="761" alt="final_chip" src="https://github.com/user-attachments/assets/aa050856-79cb-4bec-a7dd-0006935a6195" />

# Achievements

✅ RTL Successfully Synthesized

✅ Floorplanning Completed

✅ Placement Completed

✅ CTS Completed

✅ Routing Completed

✅ Timing Closure Achieved

✅ DRC Clean

✅ GDSII Generated

---

# Author

**Ananta Haque Shakal**

B.Sc. in Electrical and Electronic Engineering
