# FSM-Train-Interlocking-system
# FSM-Based Train Track Interlocking System

This repository contains the implementation of a Finite State Machine (FSM) based Train Track Interlocking System. The project ensures safe and efficient train movement across interconnected tracks by managing track switches and signals using FSM principles.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Tools Used](#tools-used)
- [Design Overview](#design-overview)
- [How to Run](#how-to-run)
- [References](#references)

---

## Introduction

Train Track Interlocking Systems play a crucial role in railway operations by ensuring that no two trains occupy conflicting paths. This project models a digital FSM to automate the control of tracks and signals, ensuring the safety and correctness of train routing.

The system is designed to:
- Prevent collisions and derailments.
- Control the state of track switches and signals.
- Respond dynamically to track availability and train movements.

---

## Features

- FSM-driven control logic for train track routing.
- Modular design for track switch and signal management.
- Fault detection and recovery mechanism.
- Real-time simulation for different track configurations.

---

## Tools Used

- **Hardware Description Languages**: Verilog/SystemVerilog for FSM implementation.
- **Simulation and Verification**:
  - ModelSim-Altera for simulation.
  - Cocotb for testbench generation.
- **EDA Tools**: 
  - Quartus/Vivado for synthesis and FPGA implementation.
  - OpenLane for additional analysis and layout design (if applicable)but in this project flow im done it also.

---

## Design Overview

### Components:
1. **Finite State Machine**: Implements the control logic for track interlocking.
2. **Switch Controller**: Manages the position of track switches.
3. **Signal Controller**: Controls the state of track signals based on FSM outputs.
4. **Fault Detection Module**: Monitors for conflicts or errors in track usage.

### Workflow:
1. Input: Train positions, desired track routes.
2. FSM: Processes inputs and determines track switch positions and signal states.
3. Output: Safely routed train paths with active signals.

---

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Haripreeth2004/FSM-Train-Interlocking-system
   unzip FSM_TTIS_Project.zip
   cd FSM_TTIS_Project
