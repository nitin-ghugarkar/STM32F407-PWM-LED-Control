# STM32F407 PWM Interfacing

## Overview

This project demonstrates **Pulse Width Modulation (PWM)** generation on the **STM32F407 Discovery Board** using **Timer 2 (TIM2)** and the **STM32 HAL Library**. PWM is used to control the brightness of an LED by varying the duty cycle while maintaining a fixed frequency.

## Hardware Required

* STM32F407 Discovery Board
* LED
* Current Limiting Resistor (220Ω)
* Jumper Wires
* Breadboard
* USB Cable

## Software Used

* STM32CubeIDE
* Embedded C
* STM32 HAL Library

## Features

* PWM generation using **TIM2**
* LED brightness control using PWM duty cycle
* Configured with STM32CubeMX
* HAL Library implementation
* Adjustable duty cycle

## Hardware Connections

* **STM32F407 Discovery Board**
* **PWM Output Pin → LED (through 220Ω resistor)**
* **LED Cathode → GND**

> *The PWM output pin depends on the timer channel configured in STM32CubeMX (e.g., TIM2 Channel 2).*

## Project Structure

```text
Core/
├── Inc/
│   └── main.h
├── Src/
│   └── main.c
```

## How to Run

1. Open the project in **STM32CubeIDE**.
2. Build the project.
3. Connect the STM32F407 Discovery Board.
4. Flash the program to the board.
5. Observe the LED brightness changing according to the configured PWM duty cycle.

## Technologies Used

* Embedded C
* STM32 HAL Library
* STM32F407 Discovery Board
* Timer 2 (TIM2)
* PWM
* GPIO


