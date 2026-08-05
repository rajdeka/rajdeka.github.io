---
title: "Monte Carlo Estimation of Pi using LFSRs"
excerpt: "Developed a hardware-based Monte Carlo simulation using Linear Feedback Shift Registers (LFSRs) in Verilog to estimate Pi.<br/><img src='/images/montecarlo.png'>"
collection: portfolio
---

For this project, I implemented a hardware-accelerated Monte Carlo simulation to estimate the value of Pi by generating random coordinate points.

### Architecture & Implementation
* **Hardware Random Number Generation:** Designed and integrated Linear Feedback Shift Registers (LFSRs) in **Verilog** to reliably generate pseudo-random X and Y coordinate pairs.
* **Coordinate Evaluation:** Implemented hardware logic to determine if the generated coordinate points fell within a designated circular boundary.
* **Data Analysis:** Extracted the simulation results from the hardware simulation into a .csv format and processed the final Pi estimation using Excel.

**Technologies Used:** Verilog, LFSRs, Hardware Simulation, Microsoft Excel.
