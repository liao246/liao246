## Projects

### [8x8 Digit Recognition Neural Network Accelerator](https://github.com/liao246/Neural-Network-Hardware-Accelerator-Proj)

The 8x8 Digit Recognition Neural Network Accelerator is a custom hardware inference engine that classifies handwritten digit images (0 to 9). Built with SystemVerilog and Python, it supports a 2-layer MLP (64 to 32 to 10) with ReLU activation, automated model training, and weight quantization. The repository uses Python scripts to export quantized weights and test vectors into memory files, which are then loaded directly by the RTL. Overall, this project demonstrates a functional hardware design flow from software-level model training to SystemVerilog implementation.

### [Hardware Accelerated Pong](https://github.com/Purdue-SoCET/intro2_S2026_team08_tt/tree/main)

coming soon

### [Systolic Array](https://github.com/liao246/Systolic-Array)

This repository contains my RTL implementation of a fully AMBA-compliant AHB-Lite subordinate interface, developed for an 8x8 weight-stationary systolic array co-processor. The interface provides memory-mapped control registers, custom data forwarding logic for hazard resolution, and robust FSM-based management of bus stalls and errors. Designed as a System-on-Chip (SoC) peripheral, the integrated design provides high-performance hardware acceleration for neural network inference within a strict 55-cycle latency constraint.
