# Round_Robin_Arbiter_using_VERILOG
Round Robin Arbiter Verilog Design

Description

This project implements a Round Robin Arbiter using Verilog. The arbiter fairly allocates access to a shared resource among four requesters (req0 to req3). The design includes a main arbiter module and a testbench for simulation.

Files

arbiter.v: Main arbiter module. Handles request and grant signals.
top.v: Testbench for the arbiter. Generates clock, reset, and request signals, and logs output for simulation.

Usage

1. Compile and simulate the Verilog files using a simulator like ModelSim or Vivado.
2. Run top.v to test the arbiter functionality.
3. Observe the grant outputs (gnt0 to gnt3) in the waveform viewer.
