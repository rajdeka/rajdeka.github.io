---
title: "Calculator Design: RCA and CLA Adders"
excerpt: "Implemented and compared 4-bit Ripple Carry and Carry Lookahead adders with a clocked 5-bit output register.<br/><img src='/images/adders.png'>"
collection: portfolio
---

I implemented a 4-bit adder twice—once as a ripple carry adder (RCA) and once as a carry lookahead adder (CLA)—and quantitatively compared their delay and area[cite: 3].

### Key Features
* Cascaded four full adders into a 4-bit ripple carry adder[cite: 3].
* Derived per-bit propagate and generate equations for a 4-bit carry lookahead adder[cite: 3].
* Integrated the adders with a clocked 5-bit register that loads results upon a button press[cite: 3].
* Analyzed the synthesized schematic in Vivado to compute the critical-path delay and total gate area[cite: 3].

**Technologies Used:** Dataflow Verilog, Xilinx Vivado, Digilent Basys3 FPGA[cite: 3].
