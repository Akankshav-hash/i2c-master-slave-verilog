# i2c-master-slave-verilog
i2c implementation of multi-master and multi-slave

# I²C Master and Slave Implementation in Verilog

## Overview

This project implements a multi-master, multi-slave I²C communication system using Verilog HDL. It models the behavior of the I²C protocol, including address transmission, acknowledgments, and shared bus communication.

## Features

* I²C Master module
* I²C Slave module
* Shared SDA/SCL bus
* Read and write operations
* ACK/NACK handling
* Multi-master and multi-slave simulation
* Modular Verilog implementation

## Project Structure

* `src/` – Verilog modules
* `tb/` – Testbench
* `docs/` – Block diagrams and waveforms
* `report/` – Internship report

## Tools Used

* Verilog HDL
* Simulation environment compatible with standard HDL workflows (EDA Playground)

## How to Run

1. Compile all source files.
2. Run the provided testbench.
3. Observe SDA, SCL, and communication waveforms.

## Results

The implementation demonstrates successful communication between masters and slaves, validating key I²C protocol operations through simulation.

## Future Scope

* Enhanced arbitration
* Clock stretching support
* Error detection mechanisms
* FPGA implementation

## Author

Akanksha V
