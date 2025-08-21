# 50 Digital Circuits in Verilog

This repository contains Verilog HDL code for a variety of fundamental digital circuits, along with their corresponding test benches and simulation results. The designs range from simple logic gates to more complex components like adders, counters, and shift registers. This project is ideal for students and hobbyists learning Verilog for FPGA or ASIC design.

## Circuits Included
The circuits are organized by category and are listed below. Each circuit has its own Verilog module (`.v`) and a test bench module (`_tb.v`).

### Combinational Logic
* Logic Gates (Gate Level & Dataflow models)
* Half Adder and Full Adder
* Half Subtractor and Full Subtractor
* Ripple Carry Adder (4-bit)
* Multiplexers (2-to-1 and 8-to-1) and Demultiplexer (1-to-8)
* Encoders (8-to-3, Priority, Decimal-BCD, Octal-Binary, Hexadecimal-Binary)
* Comparators (4-bit)
* Code Converters (Binary-Gray, Gray-Binary, BCD-Excess 3)
* Parity Generators and Checkers
* BCD-to-Seven Segment Display Converter
* Carry Look-Ahead Adder
* BCD Adder
* Tristate Buffer

### Sequential Logic
* RS, SR, JK, T, and D Flip-Flops
* Latches (RS and D)
* Counters (Asynchronous, Synchronous Up/Down, Johnson, Ring)
* Shift Registers (SISO, SIPO, PISO, PIPO)
* Master-Slave D Flip-Flop
* Finite State Machines (Mealy and Moore FSM for Sequence Detection)

## 💡 Key Features
1.Broad Coverage: The library includes a wide range of circuits, from basic logic gates and arithmetic circuits to advanced sequential logic like counters, shift registers, and Finite State Machines (FSMs).
2.Ready-to-Simulate: Every design module has a corresponding test bench, allowing for immediate simulation and waveform analysis to verify correct functionality.
3.Educational Value: The code is well-commented and structured, making it easy to understand the underlying logic and design principles.
4.Modular & Reusable: The circuits are designed in a modular fashion, enabling easy integration into larger and more complex projects.

## 🚀 Use Cases
1.Academic Learning: Students can use this repository to supplement their digital logic and Verilog courses by exploring practical, verified code examples.
2.Interview Preparation: The collection serves as an excellent tool for preparing for technical interviews related to digital design and hardware description languages.
3.Reference & Prototyping: Professional engineers can use the code as a quick reference or a starting point for developing new digital systems.

Thank you :)
