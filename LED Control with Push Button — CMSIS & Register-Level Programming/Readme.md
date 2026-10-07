# STM32 LED Control with Push Button — CMSIS & Register-Level Programming

A bare-metal STM32 GPIO project demonstrating onboard LED control using a physical push button, CMSIS, and direct register-level programming.

## 📌 Project Overview

This project implements LED control using the onboard push button of an STM32 Nucleo board.

The GPIO peripherals are configured and controlled through direct register access using CMSIS-based device definitions, without relying on STM32 HAL GPIO APIs.

## 🛠️ Hardware Used

- STM32 Nucleo-F401RE
- Onboard User LED
- Onboard User Push Button
- USB connection for programming and debugging

## 💻 Software & Tools

- STM32CubeIDE
- Embedded C
- CMSIS
- Register-Level Programming
- STM32F401RE
- ST-LINK

## ⚙️ Working

1. Enable the required GPIO peripheral clock.
2. Configure the onboard button GPIO as a digital input.
3. Configure the onboard LED GPIO as a digital output.
4. Read the button state through the GPIO input register.
5. Control the LED through the GPIO output register based on the button state.
6. Perform GPIO configuration and control using direct register manipulation and bitwise operations.

## 🔧 Key Concepts

- STM32 GPIO Architecture
- GPIO Input & Output Configuration
- Memory-Mapped Peripheral Registers
- CMSIS
- Register-Level Programming
- Bit Manipulation
- Embedded C
- Bare-Metal Firmware

## 📷 Hardware Demo

_Add a photograph of the STM32 Nucleo board running the project here._

## 🎥 Demo

_Add your project demonstration video link here._

## 🚀 Learning Outcomes

- Practical understanding of STM32 GPIO configuration at register level
- Experience with CMSIS-based microcontroller programming
- Understanding of GPIO input/output registers
- Hands-on experience with bitwise register manipulation
- Firmware testing on physical STM32 hardware
