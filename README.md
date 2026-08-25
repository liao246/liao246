## Projects

### [AHB-Lite Systolic Array Co-Processor](https://github.com/liao246/Systolic-Array)

This repository contains my RTL implementation of a fully AMBA-compliant AHB-Lite subordinate interface, developed for an 8x8 weight-stationary systolic array co-processor. The interface provides memory-mapped control registers, custom data forwarding logic for hazard resolution, and robust FSM-based management of bus stalls and errors. Designed as a System-on-Chip (SoC) peripheral, the integrated design provides high-performance hardware acceleration for neural network inference within a strict 55-cycle latency constraint.

### [Hardware Accelerated Pong](https://github.com/liao246/Hardware-Pong)

Hardware Pong is a custom ASIC implementation of the classic arcade game, engineered from the ground up to operate within a strict 1,000 standard cell limit. The project spans the entire hardware design lifecycle, moving from high-level micro-architectural specifications to iCE40 FPGA prototyping, and culminating in a fully verified OpenLane RTL-to-GDSII tapeout. To meet stringent resource constraints without sacrificing visual fidelity, the design features a custom physics engine with dynamic speed scaling and purely combinational, coordinate-based VGA rendering. This completely eliminates the need for a memory-intensive frame buffer while maintaining responsive, real-time gameplay.

### [Quantized MLP Inference Accelerator coming soon]
