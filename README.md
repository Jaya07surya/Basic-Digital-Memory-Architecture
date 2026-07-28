# Basic-Digital-Memory-Architecture
Implementation of a 4×8 RAM using D Flip-Flops, Decoder, Multiplexer, and Registers in DLS.
# 4×8 RAM Built from Basic Digital Logic

This project implements a 4×8 Random Access Memory (RAM) from basic digital components using Simulator.

The objective was to understand how RAM works internally instead of using a built-in memory block.

---

## Features

- 8-bit Registers built from D Flip-Flops
- Shared 8-bit Data Bus
- 2-to-4 Address Decoder
- Write Control Logic
- 4-to-1 Multiplexer for Read Operations
- Addressable Memory
- Modular Register Design

---

## Memory Specification

- Memory Depth : 4
- Word Width : 8 bits
- Total Storage : 32 bits (4 Bytes)

Address Mapping

00 → Register 0

01 → Register 1

10 → Register 2

11 → Register 3

---

## Components Used

- D Flip-Flops
- AND Gates
- Decoder
- Multiplexer
- Splitter / Merger
- Clock
- Input Switches
- LEDs

---

## Write Operation

1. Select the memory address.
2. Set the 8-bit input data.
3. Press the clock.
4. The selected register stores the data.

---

## Read Operation

1. Select the memory address.
2. The multiplexer automatically routes the selected register to the output.
3. No clock is required for reading.

---

## Learning Outcome

This project demonstrates how a RAM can be constructed using:

- Registers
- Address Decoding
- Multiplexers
- Shared Data Bus
- Shared Address Bus

without relying on any built-in RAM components.

---
