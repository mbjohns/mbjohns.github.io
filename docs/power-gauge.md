---
layout: page
title: "Dynamic Power Gauge Challenge"
permalink: /dynamic-power-gauge/
---

# Dynamic Power Gauge Challenge

## Mission Briefing
The power gauge of the FrostByte Flyer, essential for monitoring the sleigh's energy levels, is not functioning. Your objective is to rebuild this gauge using a potentiometer, a 10-segment LED bar graph, and a 74HC595 shift register. This setup must be assembled on a separate breadboard and retained for use in subsequent challenges.

## The Puzzle
The power gauge is crucial for understanding the sleigh's current energy status. Using the potentiometer, you will control the LED bar graph to reflect varying power levels.

## Instructions
1. Set up a potentiometer on a separate breadboard as an analog input device.
2. Connect the 10-segment LED bar graph to the 74HC595 shift register and then to the Arduino, all on the same breadboard. Make sure to use resisters! 
3. Program the Arduino to change the LED display based on the potentiometer’s input, simulating the fluctuating power levels of the sleigh.
4. Ensure that this breadboard setup is portable and can be integrated into future challenges.

## Resources
- [Reading Potentiometers](https://docs.arduino.cc/learn/electronics/potentiometer-basics)
- [LED Control with 74HC595 Shift Register](../assets/files/2.22 Eight LED with 74HC595/2.22 Eight Led with 74hc595.pdf)
- [Code Sample for LED Control with 74HC595](../assets/files/2.22 Eight LED with 74HC595/Eight_LED_with_74HC595_Flash_LED/Eight_LED_with_74HC595_Flash_LED.ino)

## Modular Design Challenge
"Assemble your tools with care and precision, for this module aids in many a decision.  
From gauging power to guiding your way, this device will be your companion, come what may."

[Back to Challenges Overview](/challenges/)
