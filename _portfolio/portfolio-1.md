---
title: "Tokyo Advertisement Sign: Scrolling LED Display"
excerpt: "Designed and implemented a multi-mode scrolling LED sign with a strict datapath and controller architecture."
collection: portfolio
---

For this project, I formalized a behavioral specification into a High-Level State Machine (HLSM) and implemented it on a Basys3 FPGA.

### Key Features
* Formalized the design by splitting the system into a datapath and a controller FSM.
* Engineered a 4-character window that pans across a longer string, reversing direction at the endpoints.
* Implemented multiple operating modes, including an OFF state and various message strings, cycled via a button press.
* Integrated clock dividers, an edge detector, a display multiplexer, and a custom letter-to-7-segment decoder.

**Technologies Used:** Verilog, High-Level State Machines (HLSM), Xilinx Vivado.
