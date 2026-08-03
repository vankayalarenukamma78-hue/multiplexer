# Multiplexer using Verilog

## Objective
Design and simulate Multiplexers using Verilog HDL.

## Description
A Multiplexer (MUX) is a combinational logic circuit that selects one input from multiple inputs based on select lines and forwards it to the output.

## Features
- 2×1 Multiplexer
- 4×1 Multiplexer
- 8×1 Multiplexer
- Verilog HDL implementation
- Testbench for verification
- Simulation waveforms

## Tools Used
- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (for waveform viewing)

## Truth Table (2×1 MUX)

| S | Output |
|---|--------|
| 0 | A |
| 1 | B |

## How to Run

Compile:

```bash
iverilog -o mux mux2x1.v mux2x1_tb.v
```

Run:

```bash
vvp mux
```

Generate waveform:

```bash
gtkwave mux.vcd
```

## Author

Your Name