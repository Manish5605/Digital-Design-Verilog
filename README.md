# 4x1 Multiplexer using Parameterized 2x1 Multiplexers (Verilog)

## Overview

This project implements a 4x1 Multiplexer in Verilog HDL using a hierarchical design approach. The design is constructed using three parameterized 2x1 multiplexers.

## Features

* Parameterized data width
* Hierarchical RTL design
* Synthesizable in Xilinx Vivado
* Testbench included for functional verification

## Design Hierarchy

4x1 MUX
├── 2x1 MUX
├── 2x1 MUX
└── 2x1 MUX

## Files

### src/

* Mux_Parameterized.v : Parameterized 2x1 Multiplexer
* Mux_4x1.v : 4x1 Multiplexer implementation

### tb/

* Mux_tb.v : Testbench

## Simulation

The design was verified using Vivado XSIM.

## Synthesis Results

* Slice LUTs Used: 4
* FPGA Tool: Xilinx Vivado

## Author

Manish
Electronics Engineering Student
