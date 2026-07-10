# Project Specification

## Project Title

**Real-Time Execution of an Adaptive Kalman Filter Algorithm on an Embedded ARM Processor for Sensorless Rotor Position Tracking of a BLDC Motor**

---

## Project Objective

To develop a real-time sensorless BLDC motor control system that estimates rotor position and speed using an Adaptive Kalman Filter implemented on an STM32 ARM Cortex-M microcontroller, eliminating the need for rotor position sensors during motor operation.

---

## Scope

The project includes:

* Hardware selection and integration
* BLDC motor control
* Sensorless rotor position estimation
* Adaptive Kalman Filter implementation
* Embedded firmware development
* Experimental validation
* Performance evaluation

The project does not focus on designing custom semiconductor devices or developing a new motor.

---

## Functional Requirements

* Control a three-phase BLDC motor.
* Generate PWM signals for inverter control.
* Measure motor currents and DC bus voltage.
* Execute the Adaptive Kalman Filter in real time.
* Estimate rotor electrical position and speed.
* Drive the motor using estimated rotor position.
* Validate estimated position using Hall sensor feedback (reference only).

---

## Non-Functional Requirements

* Real-time execution on an STM32 microcontroller.
* Reliable sensorless operation.
* Modular software architecture.
* Easy hardware maintenance and debugging.
* Comprehensive documentation.

---

## Expected Deliverables

* Working hardware prototype
* Embedded firmware
* Hardware documentation
* Experimental results
* Performance analysis
* Final project report
* Presentation
