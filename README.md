# UART Transceiver in Verilog

This repository contains the Verilog implementation of a UART (Universal Asynchronous Receiver/Transmitter) transceiver, designed to handle asynchronous serial communication with configurable baud rates. The project features both transmission (TX) and reception (RX) of 8-bit data, using a Finite State Machine (FSM) approach.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Simulation](#simulation)

## Overview

The UART transceiver in this project implements a basic serial communication protocol to transmit and receive 8-bit data between devices. It consists of two parts:

1. **Transmitter (TX)**: Serializes 8-bit parallel data and transmits it over the TX line.
2. **Receiver (RX)**: Deserializes the data received from the RX line back into parallel 8-bit data.

The UART communication in this project follows the standard frame format of:
- 1 start bit (low),
- 8 data bits (least-significant-bit first),
- 1 stop bit (high).

## Features

- Configurable baud rate for data transmission.
- 8-bit data transmission with start and stop bits.
- Separate FSMs for TX and RX logic.
- Designed for easy simulation and testing with provided testbench.

## Simulation
![uart_simulation](https://github.com/user-attachments/assets/65881a07-8d6e-4cb6-927a-46809e36ed7a)

Thank You!!!!
