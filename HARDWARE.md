# Hardware Selection

This document records all hardware decisions made during the project. Components may be updated as the design progresses.

---

# Processing Unit

| Component               | Status              |
| ----------------------- | ------------------- |
| STM32G431RB (Preferred) | Pending Procurement |

Reason:

* ARM Cortex-M4
* Floating Point Unit (FPU)
* High-speed ADC
* Advanced motor-control timers
* Suitable for real-time Adaptive Kalman Filter execution

---

# Motor

| Component                               | Status            |
| --------------------------------------- | ----------------- |
| 24 V Three-Phase BLDC Motor (150–200 W) | Pending Selection |

Requirements:

* Hall sensors (for validation only)
* Datasheet with electrical parameters
* Three-phase operation

---

# Power Stage

| Component                       | Status         |
| ------------------------------- | -------------- |
| Ready-made Three-Phase Inverter | To Be Selected |

Reason:

* Improves reliability
* Reduces development time
* Allows focus on estimation and control algorithms

---

# Gate Driver

Integrated with the selected inverter module.

---

# Current Measurement

| Component                      | Quantity |
| ------------------------------ | -------- |
| INA240 Current Sense Amplifier | 2        |
| Precision Shunt Resistors      | 2        |

Configuration:

* Low-side current sensing
* Two measured phase currents
* Third phase current calculated in software

---

# Voltage Measurement

| Component              | Quantity |
| ---------------------- | -------- |
| DC Bus Voltage Divider | 1        |

Purpose:

* Measure inverter DC bus voltage
* ADC input to STM32

---

# Power Supply

| Component    | Status            |
| ------------ | ----------------- |
| 24 V DC SMPS | Pending Selection |

Additional Supplies:

* 12 V for gate driver/inverter (if required)
* 5 V / 3.3 V for controller electronics

---

# Communication

* USB
* ST-Link
* UART (Debugging)

---

# Hardware Status

| Component            | Decision   |
| -------------------- | ---------- |
| STM32 Controller     | ✅ Selected |
| BLDC Motor           | ⏳ Pending  |
| Three-Phase Inverter | ⏳ Pending  |
| Current Sensors      | ✅ Selected |
| Voltage Sensor       | ✅ Selected |
| Power Supply         | ⏳ Pending  |
