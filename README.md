# STM32 Signal Acquisition & Closed-Loop Control

A real-time embedded system built on an STM32F446RE that samples analog signals using the ADC, processes data on the microcontroller, and actuates a servo via hardware PWM with UART telemetry for monitoring.

---

## Project Overview

This project demonstrates an end-to-end embedded signal acquisition and actuation pipeline implemented entirely on a microcontroller. An analog input from a joystick potentiometer is sampled using the STM32’s 12-bit ADC, processed in real time by the MCU, and used to control a servo motor through hardware-generated PWM. UART telemetry provides continuous visibility into system behavior for debugging and validation.

---

## Hardware & Tools

- STM32 Nucleo-F446RE (ARM Cortex-M4)
- 12-bit ADC
- Hardware timers (PWM generation)
- SG90 micro servo
- 2-axis joystick potentiometer
- UART (PuTTY for telemetry)
- STM32CubeIDE
- Embedded C

---

## Key Features

- Timer-driven ADC sampling of analog input signals
- Hardware-based PWM generation for precise servo control
- Closed-loop joystick-to-servo control
- UART telemetry for real-time system monitoring
- Deadband logic to mitigate ADC noise

---

## Demo

🎥 Video demonstration: https://youtu.be/P8PqJ9iEa18
🎥 Video demonstration: https://youtu.be/upl2huopSv4

---

## What This Project Demonstrates

- Real-time embedded system design
- Peripheral configuration (ADC, timers, PWM, UART)
- Signal flow reasoning from sensor to actuator
- Hardware debugging and validation
- Separation of control logic and telemetry

---

## Future Improvements

- DMA-based ADC sampling for improved efficiency
- Interrupt-driven control loop
- Digital filtering of noisy inputs
- Extension to multi-channel signal acquisition


