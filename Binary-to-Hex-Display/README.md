# Counter in DE1-SoC

This repository contains the code and resources for implementing a simple counter using the DE1-SoC FPGA board. The project demonstrates basic FPGA design and hardware description using Verilog. The counter operates on the DE1-SoC's hardware and is a useful starting point for anyone learning FPGA programming or working with this specific board.

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Verilog Code Explanation](#verilog-code-explanation)
- [Usage](#usage)
- [License](#license)

## Project Overview

This project implements a simple 4-bit counter on the DE1-SoC FPGA development board. The counter increments on each clock cycle and can be reset using a push-button on the board. It also features an LED display that shows the current count value. The primary goal of this project is to demonstrate basic FPGA functionality and Verilog design principles.

## Getting Started

### Hardware Requirements

- **DE1-SoC FPGA Board**: The project is designed for the DE1-SoC FPGA development board by Terasic.
- **External Components**: No additional hardware is required apart from the FPGA board itself.

### Software Requirements

- **Quartus Prime Software**: To compile and program the FPGA using Verilog code.
- **Verilog Compiler**: Quartus Prime provides the necessary tools to synthesize the Verilog code and configure the FPGA.

### Setting Up

1. Download and install [Quartus Prime Software](https://www.intel.com/content/www/us/en/software/programmable/quartus-prime/overview.html).
2. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/tariftasfiq/counter-in-DE1-SoC.git
    ```
3. Open the project in Quartus Prime and compile the design.
4. Follow the instructions in the software to program the DE1-SoC board.

## Verilog Code Explanation

The Verilog code in this repository implements the following features:
- **Counter Module**: A 4-bit counter that increments on every clock pulse.
- **Button Reset**: The counter can be reset using a push-button on the board.
- **LED Display**: The counter value is shown on the onboard LEDs.

The main files in this repository include:
- `counter.v`: The Verilog code for the counter module.
- `top.v`: The top-level module that connects the counter to the FPGA pins and handles the reset and LED display.

## Usage

1. Once the project is compiled and programmed onto the DE1-SoC board, the counter will start incrementing automatically.
2. Press the reset button on the DE1-SoC to reset the counter value.
3. Observe the current value of the counter on the onboard LEDs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
