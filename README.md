# STM32 Signal Acquisition & Closed-Loop Control

A real-time embedded system built on an STM32F446RE that samples analog signals using the ADC, processes data on the microcontroller, and actuates a servo via hardware PWM with UART telemetry for monitoring.

---

## Project Overview

This project demonstrates an end-to-end embedded signal acquisition and actuation pipeline implemented entirely on a microcontroller. An analog input from a joystick potentiometer is sampled using the STM32’s 12-bit ADC, processed in real time by the MCU, and used to control a servo motor through hardware-generated PWM. UART telemetry provides continuous visibility into system behavior for debugging and validation.

---

## System Architecture

