# LEGv8 CPU

LEGv8 Single-Cycle and 5-Stage Pipeline CPU implemented in Verilog.

## Architecture

Single Cycle CPU datapath

PC → Instruction Memory → Register File → ALU → Data Memory → Register Write

## Features

- LEGv8 instruction subset
- Single Cycle CPU
- 5-stage Pipeline CPU (planned)
- Verilog RTL implementation

## Simulation

Testbench-based functional verification performed.

## FPGA Implementation

Timing analysis performed in Vivado.

| Clock | Result |
|------|------|
| 100 MHz | Timing violation |
| 80 MHz | Timing closure |

## Repository Structure
