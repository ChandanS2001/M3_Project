# M3_Project

Abstract

A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage. As a result, this system is proposed to address these issues. The project's goals are to improve ageing cars' systems by giving automated transmission. wiping system, to improve the system by incorporating a sensor and actuator, and to create a simple software that would completely operate with the system the framework This proposed wiper system's principle is comparable to those of other existing conventional wipers.Despite the fact that this system will be upgraded to an automatic control system using a Peripheral Interface to remove water from the windscreen.The automated rain wiper technology detects rain and activates the car's automatic rain wipers without the need for the driver to intervene. The method was created to reduce driver distractions and allow them to concentrate on their primary duty of driving. The manual adjustment of windshield wipers when driving in rain has been eliminated thanks to the creation of this device. In bad weather circumstances, a driver's attention being diverted from the road for a few seconds to change a knob could result in a car accident. To detect rain and its intensity, the system employs a combination of impedance and rain sensor.The system includes a controller that receives input signals from the sensors and controls the windshield wipers' operation based on those signals. The goal of this initiative is to assist prevent accidents that occur when a driver tries to clear the windscreen while it is raining, diverting his or her attention away from the road while switching on and off the wiper. On rainy days, the act of showering water on the front glass of our vehicle is a problem. When driving a car, the driver cannot see other vehicles on the road. So he attempts to clean the glass with the wiper, which requires him to switch on the wiper frequently, which may result in a vehicle collision. If any form of sensor is placed on the window and detects the act of sprinkling water, the wiper will operate automatically. When water falls on the sensor, it sends a signal to the system, which activates the wiper motor. The wiper will stop if the sensor does not detect any water. This will mitigate the flaws that were mentioned at the outset. Another feature of this design is that when the engine is turned off, the wiper will automatically push up from the windscreen.

Requirements

# Requirements

Installable
•	GNU Toolchain
•	STM Cube IDE
Downloadable
•	Xpack Packages
•	Windows Build Tools
•	Open OCD
•	Qemu

## High Level Requirements
| High Level Requirements  | Description |
| ------------- | ------------- |
| HLR1  | Microcontroller - STM32F4 board |
| HLR2  | Software for simulation |
| HLR3  | LED |
| HLR4  | Push button |

## Low Level Requirements
| Low Level Requirements	  | Description |
| ------------- | ------------- |
| HLR1_LLR1 | STM32F4 discovery  |
| HLR2_LLR2 | avr gcc/gnu |
| HLR2_LLR3 | xPack - Qemu, xPack - Windows Build Tool, Pack - OpenOCD |
| HLR2_LLR3 | STM32 Cube IDE |
| HLR3_LLR4 | I/O PD12, PD13, PD14, PD15 on STM32F407VGT6 |
| HLR4_LLR5 | Pull-down resistor/ Pull-up resistor  |
| HLR4_LLR6 | PA0 digital pin  |


4W'S and 1H

What
•	It is the controlling of car wiper system using the STM32.
Where
•	This project is mainly used in Automobile industries.
Why
•	The main objective of this project is to control the wiper system by using the LED.
HOW
•	This project is implemented using Embedded C Program based on arm based microcontroller.

Design

Block Diagram Of Wiper Control System Using STM32

![image](https://user-images.githubusercontent.com/102878158/168502242-2a8d2dba-9f15-4a4a-870c-d87cac727fde.png)
