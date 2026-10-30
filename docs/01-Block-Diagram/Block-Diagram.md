---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview

This block diagram illustrates the temperature and display portion of the plant monitoring system, including its power distribution, sensors, microcontroller, actuators, and team connections. A 9V, 1.3A wall adapter supplies power to an L7805 voltage regulator, which provides a regulated 5V supply to the system. The PIC18F57Q43 Curiosity Nano serves as the central controller, receiving digital temperature measurements from the DS18B20 and analog signals from additional sensors through its ADC inputs. The controller processes the collected data and communicates with the OLED display through UART while also controlling output devices such as the status LED. Shared digital and analog connectors allow the different team-developed subsystems to interface with the main controller.

I connect to all three of the boards, recieving information from one and two and sending information to three. 

## Example Block Diagram 
![Indivial Block diagram](blockdiagram_TO.drawio.png)

draw.io source files included [here](https://drive.google.com/file/d/1r8vSazPCn00a6qEjoiITMU8ggQQN10Ez/view)