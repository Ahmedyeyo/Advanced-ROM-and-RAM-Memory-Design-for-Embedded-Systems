# Advanced ROM and RAM Memory Design for Embedded Systems

High-performance, FPGA-optimized memory systems for versatile embedded applications.

## Project Overview
This project implements robust ROM (Read-Only Memory) and RAM (Random Access Memory) modules tailored for embedded systems. Designed in VHDL, these modules focus on reliability, efficiency, and seamless integration with FPGA-based CPUs. The memory systems support a wide range of operations, including instruction storage, data handling, and memory-mapped I/O.

Key highlights include:
1. **ROM Design**: Fixed instruction storage for CPU operations with optimized access time.
2. **RAM Implementation**: Dynamic data storage with efficient read/write mechanisms.
3. **FPGA Deployment**: Comprehensive testing and deployment on DE10-Lite FPGA boards.

## Features
- **Parameterizable Memory Sizes**: Easily adjustable memory depths and widths for diverse applications.
- **Dual-Port RAM**: Simultaneous read and write operations for enhanced performance.
- **Memory-Mapped I/O**: Efficient peripheral interfacing through memory mapping.
- **Testbench Validation**: Thorough simulations for functional verification and performance evaluation.

## File Structure
- **src/**: VHDL source files for ROM and RAM modules.
- **doc/**: Design specifications and memory usage analysis.
- **simulation/**: ModelSim files for testbench-driven validation.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Memory_Design.git
