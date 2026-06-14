# CMOS-Inverter-Project
A CMOS Inverter Design and Analysis project implemented using LTspice. The project includes circuit design, transient simulation, switching analysis, propagation delay measurement, performance evaluation, and validation of CMOS inverter operation.




# CMOS Inverter Design and Analysis

## Project Overview

This project presents the design, simulation, and analysis of a CMOS (Complementary Metal Oxide Semiconductor) Inverter using LTspice. The CMOS inverter is one of the most fundamental building blocks in digital integrated circuits and is widely used in VLSI design.

The objective of this project is to design a CMOS inverter circuit, simulate its behavior, analyze switching characteristics, measure propagation delay, and study the effect of transistor sizing on circuit performance.

---

## Objectives

- Design a CMOS inverter using PMOS and NMOS transistors.
- Simulate the inverter using LTspice.
- Analyze input and output switching characteristics.
- Measure propagation delay.
- Study power consumption characteristics.
- Understand transistor sizing optimization.
- Validate the inverter operation.

---

## Software Used

- LTspice XVII / LTspice 26
- Windows Operating System

---

## Circuit Description

A CMOS inverter consists of:

- One PMOS transistor connected between VDD and output.
- One NMOS transistor connected between output and ground.
- Common gate connection used as the input.
- Common drain connection used as the output.

### Operating Principle

- When Vin = 0 V:
  - PMOS turns ON
  - NMOS turns OFF
  - Vout = VDD

- When Vin = VDD:
  - PMOS turns OFF
  - NMOS turns ON
  - Vout = 0 V

Thus, the output is always the logical complement of the input.

---

## Simulation Parameters

| Parameter | Value |
|------------|--------|
| Supply Voltage (VDD) | 5 V |
| Input Signal | Pulse Source |
| Analysis Type | Transient Analysis |
| Technology | CMOS |

---

## Results

### Circuit Schematic
The CMOS inverter circuit was successfully designed in LTspice.

### Input and Output Waveforms
The simulation results show that:

- Input HIGH produces Output LOW.
- Input LOW produces Output HIGH.
- Proper inverter action is achieved.

### Propagation Delay
The propagation delay was measured using LTspice cursors.

Measured Delay:

- tpd ≈ 186.57 µs

### Performance Analysis

- Fast switching behavior observed.
- Low static power consumption.
- High noise immunity.
- Suitable for digital logic applications.

---

## Optimization of Transistor Sizing

To achieve balanced rise and fall times:

- NMOS Width = 1 µm
- PMOS Width = 2 µm
- Length = 180 nm

Since hole mobility is lower than electron mobility, the PMOS width is generally chosen larger than the NMOS width.

---

## Applications

- Logic Gates
- Microprocessors
- Digital IC Design
- VLSI Systems
- Memory Circuits
- Embedded Systems

---

## Conclusion

The CMOS inverter was successfully designed and simulated using LTspice. The output waveform was found to be the complement of the input waveform, validating correct inverter operation. Propagation delay was measured, switching characteristics were analyzed, and transistor sizing considerations were discussed. The project demonstrates the fundamental operation and performance of CMOS inverter circuits used in modern digital electronics.

---

## Repository Contents

- Draft4.asc (LTspice Schematic)
- Circuit.png
- Waveform.png
- Delay.png
- CMOS_Inverter_Report.pdf
- README.md

---

## Author

Karthick M

Electronics and Communication Engineering (ECE)

Academic Mini Project – CMOS Inverter Design and Analysis
