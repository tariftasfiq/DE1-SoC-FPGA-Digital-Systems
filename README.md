# DE1-SoC FPGA Digital Systems Using Verilog

A collection of FPGA-based digital system design projects implemented using **Verilog HDL**, **Intel Quartus Prime**, and the **Terasic DE1-SoC development board**.

This repository combines two projects demonstrating digital logic design, counter implementation, binary-to-hexadecimal conversion, and seven-segment display interfacing.

---

## Projects

### 1. Up/Down Counter with Reset

An FPGA-based digital counter implemented using Verilog HDL, featuring up-counting, down-counting, and reset functionality.

**Features:**
- Supports both up-counting and down-counting.
- Includes reset functionality.
- Displays count values (0–9) in binary through onboard LEDs.
- Displays hexadecimal count values on a seven-segment display.
- Implemented and tested on the DE1-SoC FPGA board.

**Project Directory:** `Counter/`

**Quartus Project File:** `counter_7seg.qpf`

### 2. Binary-to-Hexadecimal Display on Seven-Segment Display

A digital system that accepts a 4-bit binary input through the DE1-SoC onboard switches and displays the corresponding hexadecimal value on a seven-segment display.

**Features:**
- Accepts 4-bit binary input through onboard switches.
- Converts binary input into its corresponding hexadecimal representation.
- Displays the converted value on a seven-segment display.
- Implements the conversion and display logic using Verilog HDL.

**Project Directory:** `Binary-to-Hex-Display/`

**Quartus Project File:** `seven_segment_display.qpf`

---

## Hardware and Software Requirements

| Component | Description |
|---|---|
| FPGA Development Board | Terasic DE1-SoC |
| FPGA Device | Intel Cyclone V |
| Hardware Description Language | Verilog HDL |
| Design Software | Intel Quartus Prime |
| Programming Interface | USB-Blaster |

---

## Repository Structure

```text
DE1-SoC-FPGA-Digital-Systems/
│
├── README.md
│
├── Counter/
│   ├── counter_7seg.qpf
│   ├── counter_7seg.qsf
│   ├── counter_7seg.v
│   ├── DE1-SoC.qsf
│   └── ...
│
└── Binary-to-Hex-Display/
    ├── seven_segment_display.qpf
    ├── seven_segment_display.qsf
    ├── seven_segment_display.v
    ├── DE1-SoC.qsf
    └── ...
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tariftasfiq/DE1-SoC-FPGA-Digital-Systems.git
```

### 2. Open a Project in Quartus Prime

Choose the project you want to run:

**For the Up/Down Counter:**
1. Navigate to the `Counter/` directory.
2. Open `counter_7seg.qpf` in Intel Quartus Prime.

**For the Binary-to-Hexadecimal Display:**
1. Navigate to the `Binary-to-Hex-Display/` directory.
2. Open `seven_segment_display.qpf` in Intel Quartus Prime.

### 3. Compile and Program the FPGA

1. Review the Verilog source code and pin assignments.
2. Compile the project using Quartus Prime.
3. Connect the DE1-SoC board to your computer through the USB-Blaster interface.
4. Open the Programmer in Quartus Prime.
5. Select the generated programming file and program the FPGA.
6. Test the design using the onboard switches, buttons, LEDs, and seven-segment displays.

---

## Learning Outcomes

These projects provided practical experience with:

- Digital system design using Verilog HDL.
- Combinational and sequential logic implementation.
- Up/down counter design and reset functionality.
- Binary-to-hexadecimal conversion.
- Seven-segment display interfacing.
- FPGA compilation and hardware programming.
- Intel Quartus Prime design and simulation workflow.

---

## Author

**Sheikh Tariful Islam**

## Repository

[DE1-SoC FPGA Digital Systems – GitHub](https://github.com/tariftasfiq/DE1-SoC-FPGA-Digital-Systems)
