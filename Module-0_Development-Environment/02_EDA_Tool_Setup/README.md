# EDA Tool Setup

## Overview

This section documents the setup and verification of the open-source EDA tools used throughout the RTL design and synthesis workflow.

## Tools Covered

### Icarus Verilog

Used for:

- Verilog compilation
- RTL simulation
- Testbench execution
- VCD waveform generation

### GTKWave

Used for:

- Viewing simulation waveforms
- Analyzing signal transitions
- Debugging RTL behavior
- Verifying simulation results

### Yosys

Used for:

- RTL synthesis
- Design elaboration
- Logic optimization
- Netlist generation

## Toolchain

```text
Verilog RTL
     ↓
Icarus Verilog
     ↓
Simulation
     ↓
VCD File
     ↓
GTKWave
     ↓
Waveform Analysis
     ↓
Yosys
     ↓
RTL Synthesis
