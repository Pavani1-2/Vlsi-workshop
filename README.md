# VLSI RTL Design and Synthesis

## Introduction

This repository contains my learning and implementation work on RTL design and synthesis using Verilog HDL.

The work was carried out using the VLSI Design and Synthesis Workshop environment with tools such as Verilog, Yosys, GTKWave and SKY130 standard-cell libraries.

## Objectives

- Learn RTL design using Verilog HDL.
- Understand combinational and sequential circuits.
- Write and simulate Verilog designs.
- Verify designs using testbenches.
- Understand RTL synthesis using Yosys.
- Study synthesized netlists.
- Understand hierarchical designs.
- Analyze waveforms using GTKWave.
- Understand the mapping of RTL designs to SKY130 standard cells.

## Tools Used

- Verilog HDL
- Yosys
- GTKWave
- GVim
- SKY130 Standard Cell Library
- Linux / Ubuntu
- Oracle VirtualBox

## Experiments

### 1. Multiplexer

A 2:1 multiplexer was designed using Verilog.

**Function:**

- `sel = 0` → `y = i0`
- `sel = 1` → `y = i1`

The design was simulated and verified using GTKWave.

### 2. Multiple Modules

A hierarchical design was implemented using multiple Verilog modules.

The design consists of:

- `sub_module1`
- `sub_module2`
- `multiple_modules`

The output of one module is connected to another module through an intermediate net.

### 3. D Flip-Flop

D flip-flop designs were studied and simulated with different reset/set configurations.

The following designs were explored:

- D Flip-Flop with asynchronous reset
- D Flip-Flop with asynchronous set
- D Flip-Flop with synchronous reset

### 4. RTL Synthesis

The Verilog RTL designs were synthesized using Yosys.

The synthesis process includes:

1. Reading the Verilog source.
2. Elaborating the design.
3. Performing RTL optimization.
4. Mapping the design to standard cells.
5. Generating the synthesized netlist.
6. Checking the synthesized design.

### 5. SKY130 Standard Cell Mapping

The synthesized designs were mapped to SKY130 standard cells.

Examples of mapped cells include:

- `sky130_fd_sc_hd__and2_0`
- `sky130_fd_sc_hd__or2_0`
- `sky130_fd_sc_hd__mux2_1_4_`

## Simulation

Testbenches were used to verify the functionality of the designs.

GTKWave was used to observe:

- Input signals
- Clock signals
- Reset/set signals
- Output signals

## Results

The RTL designs were successfully simulated and synthesized.

The simulation waveforms confirmed the expected behavior of the implemented circuits.

The synthesized netlists showed the corresponding SKY130 standard-cell implementation.

## Conclusion

This work provided practical understanding of RTL design, Verilog simulation, hierarchical design, synthesis using Yosys, waveform analysis using GTKWave, and standard-cell mapping using the SKY130 technology library.

## Future Work

- Design more complex RTL circuits.
- Perform timing analysis.
- Study area and power optimization.
- Explore physical design flow.
- Implement larger digital systems.
