# Adaptive Kalman Filter-Based Sensorless BLDC Motor Control

A research-oriented embedded systems project focused on implementing a real-time Adaptive Kalman Filter (AKF) for sensorless rotor position estimation of a three-phase BLDC motor using an STM32 ARM Cortex-M microcontroller.

The project replaces conventional rotor position sensors, such as Hall-effect sensors and rotary encoders, with a model-based state estimation algorithm that estimates rotor position and speed from electrical measurements. The objective is to develop a complete sensorless motor control system capable of accurate real-time rotor position tracking.

This repository documents the complete engineering workflow, including hardware selection, system architecture, mathematical modeling, embedded firmware development, hardware integration, testing, validation, and performance evaluation.

## Objectives

* Design a sensorless BLDC motor control system.
* Implement an Adaptive Kalman Filter on an STM32 microcontroller.
* Estimate rotor position and speed using electrical measurements.
* Validate estimation results against Hall sensor feedback.
* Evaluate accuracy, computational performance, and robustness.

## Technologies

* STM32 ARM Cortex-M
* Embedded C
* Adaptive Kalman Filter
* BLDC Motor Control
* Power Electronics
* Control Systems
* Real-Time Embedded Systems

## Repository Structure

* `PROJECT_SPECIFICATION.md` – Project objectives, scope, and requirements
* `HARDWARE.md` – Selected components and hardware design
* `SYSTEM_ARCHITECTURE.md` – Overall hardware and software workflow (to be added)
* `DEVELOPMENT_LOG.md` – Progress tracking
* `BOM.md` – Bill of Materials

## Project Status

🚧 **Planning & Hardware Selection**
