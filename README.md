# Fixed-Point Tanh Accelerator

## Overview
This project implements a **23-stage pipelined tanh accelerator** in SystemVerilog.  
It uses an **11th-degree Taylor approximation** in **Q2.12 fixed-point format** and supports a **ready/valid handshake protocol** for stall-safe streaming operation.

## Features
- 23-stage pipeline with optimized latency.
- Q2.12 fixed-point arithmetic for efficient resource usage.
- Ready/valid handshake for robust streaming data transfer.
- Achieves **180+ MHz timing closure** on FPGA (synthesized with Vivado).

## Usage
1. Open in **Vivado** 
2. Run synthesis and implementation.
3. Run simulation with the testbench in `tb/` to verify functionality.
