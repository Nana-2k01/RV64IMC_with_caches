# RV64IMC with Caches

A RISC-V 64-bit processor implementation supporting the RV64IMC instruction set architecture with integrated cache memory system.

## Overview

This project implements a complete RISC-V 64-bit processor core with the following key features:
- **RV64IMC Instruction Set**: Supports 64-bit RISC-V base integer instructions, multiplication/division extensions, and compressed instructions
- **Cache System**: Integrated instruction and data caches for improved performance
- **Hardware Description**: Written primarily in Verilog and SystemVerilog
- **Verification**: Includes C++ testbenches and verification infrastructure

## Architecture

### Core Features
- 64-bit RISC-V processor core
- RV64IMC instruction set support:
  - **RV64I**: 64-bit base integer instruction set
  - **M**: Standard extension for integer multiplication and division
  - **C**: Standard extension for compressed instructions
- Integrated cache memory system
- Pipeline architecture for improved performance

### Cache System
- Instruction cache (I-cache)
- Data cache (D-cache)
- Configurable cache parameters
- Cache coherency support


## Getting Started

### Prerequisites
- Verilog/SystemVerilog simulator (e.g., ModelSim, VCS, or Verilator)
- Make utility
- C++ compiler (for testbenches)

### Building and Simulation

1. Clone the repository:
   ```bash
   git clone https://github.com/Nana-2k01/RV64IMC_with_caches.git
   cd RV64IMC_with_caches
   ```

2. Build the project:
   ```bash
   make
   ```

3. Run simulations:
   ```bash
   make sim
   ```

4. Run tests:
   ```bash
   make test
   ```

## Technical Specifications

### Instruction Set Support
- **RV64I**: 64-bit base integer instructions
- **M Extension**: Multiplication and division operations
- **C Extension**: 16-bit compressed instructions for code density

### Cache Configuration
- Configurable cache size and associativity
- Write-back and write-through policies
- Cache line size optimization

### Performance Features
- Pipelined execution

## Verification

The project includes comprehensive verification infrastructure:
- Unit tests for individual modules
- Integration tests for the complete system
- Performance benchmarks
- Compliance tests for RISC-V specification

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development Guidelines
- Follow Verilog/SystemVerilog coding standards
- Include appropriate testbenches for new features
- Update documentation for any architectural changes
- Ensure all tests pass before submitting changes

## License

This project is open source. Please check the license file for specific terms and conditions.

## References

- [RISC-V International](https://riscv.org/)
- [RISC-V Instruction Set Manual](https://riscv.org/specifications/)
- [RISC-V Privileged Architecture](https://riscv.org/specifications/privileged-isa/)

## Contact

For questions or support, please open an issue on GitHub or contact the maintainer.

---

**Note**: This is a hardware implementation project. Ensure you have the appropriate tools and knowledge for Verilog/SystemVerilog development and simulation.
