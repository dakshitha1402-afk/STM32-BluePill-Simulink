# STM32 Blue Pill LED Blinking Using MATLAB Simulink

## Overview

This project demonstrates embedded systems development using MATLAB Simulink and the STM32F103C8T6 Blue Pill microcontroller.

The objective is to generate firmware from a Simulink model and deploy it to a physical microcontroller to control its onboard LED.

## Hardware

* STM32F103C8T6 Blue Pill
* ST-Link V2 programmer/debugger
* Connecting wires

## Software and Tools

* MATLAB
* Simulink
* STM32 Microcontroller Blockset
* STM32CubeMX
* STM32CubeProgrammer

## GPIO Configuration

* GPIO Port: GPIOC
* Pin: PC13
* Function: Digital output

## Implementation

1. Created a Simulink model using a Pulse Generator and Digital Port Write block.
2. Configured GPIO PC13 as an output.
3. Generated firmware using the STM32 development workflow.
4. Connected the Blue Pill using ST-Link V2.
5. Successfully deployed the model to the microcontroller.

## Result

The firmware was successfully deployed to the STM32 Blue Pill, and the LED-blinking behavior was observed.

## Learning Outcomes

* GPIO configuration and digital output control
* Model-based embedded development
* Firmware generation using Simulink
* Programming an STM32 microcontroller using ST-Link V2
* Troubleshooting hardware deployment

## Future Improvements

* Interface external LEDs and push buttons.
* Read temperature and humidity sensor data.
* Explore sensor-based embedded applications.

## Project Status

Completed: Initial LED-blinking demonstration.
