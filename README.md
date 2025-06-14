# riscv32i

A simple implementation of a RISC-V 32I CPU core.

## Overview

This project implements a CPU core compatible with the RISC-V 32I instruction set architecture. It is designed for educational purposes, experimentation, and as a starting point for more advanced RISC-V projects.

## Features

- Implements the RISC-V 32I base integer instruction set
- Modular and extensible code structure
- Suitable for simulation and synthesis
- Clear separation between datapath and control logic

## Getting Started

### Prerequisites

- Hardware description language tools (e.g., Verilog/VHDL simulator, synthesis toolchain)
- RISC-V toolchain (optional, for testing with assembly programs)

### Cloning the Repo

```sh
git clone https://github.com/AnitVarghese/riscv32i.git
cd riscv32i
```

### Building and Simulation

Describe how to build and simulate your core here. For example, if using Verilog and Icarus Verilog:

```sh
iverilog -o riscv32i_tb testbench.v riscv32i.v
vvp riscv32i_tb
```

Update this section with instructions relevant to your files and toolchain.

## Directory Structure

```
riscv32i/
├── src/          # Source files for the CPU core
├── test/         # Testbenches and test programs
├── docs/         # Documentation
└── README.md
```

## Usage

- Integrate the core into your FPGA/ASIC design flow
- Modify and extend for custom instructions or features
- Run provided testbenches to verify functionality

## Contributing

Contributions are welcome! Please open issues and pull requests to suggest improvements or report bugs.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## References

- [RISC-V ISA Specification](https://riscv.org/technical/specifications/)
- [RISC-V Community](https://riscv.org/)
