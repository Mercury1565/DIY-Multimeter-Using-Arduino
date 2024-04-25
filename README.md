# DIY-Multimeter-Using-Arduino

This project utilizes Arduino to create a simple yet functional multimeter for measuring voltage, current, resistance, and performing continuity tests. The multimeter is designed to be customizable and can be easily expanded or modified according to your needs.

## Table of Contents

- Introduction
- Features
- Hardware Requirements
- Setup Instructions
- Usage
- Customization

## Introduction

This project aims to provide hobbyists and electronics enthusiasts with a DIY solution for a multimeter, the most essential equipment for an electrical engineer, using readily available Arduino components. By following the provided instructions, you can build your own multimeter capable of measuring voltage, current, resistance, and performing continuity tests.

## Features

- Measurement of Voltage: Measures voltage in the range of 0-25V.
- Measurement of Current: Measures current in two scales: 0-1A and >1A.
- Measurement of Resistance: Measures resistance in four different scales: 0-2kΩ, 2-20kΩ, 20-200kΩ, and 200-1000kΩ.
- Continuity Test: Audible indication of continuity using a piezo buzzer.

## Hardware Requirements

To build this DIY multimeter, you will need the following hardware components:

- Arduino board (e.g. Arduino Uno)
- Liquid Crystal Display (LCD) module 
- Potentiometer (for mode selection)
- Pushbuttons (for scale adjustment)
- Resistors and operational amplifiers for current measurement
- Piezo buzzer for continuity test
- Jumper wires and breadboard (optional)

## Setup Instructions

- Connect the hardware components according to the provided Arduino sketch and the pin configurations.
- Upload the provided Arduino sketch to your Arduino board using the Arduino IDE.
- Power up your Arduino board.
- Your DIY multimeter is now ready to use.

![Screenshot from 2024-04-25 16-10-49](https://github.com/Mercury1565/DIY-Multimeter-Using-Arduino/assets/78665128/9e243116-7e10-4af0-86d8-bdc8de229993)

## Usage

- Upon powering up the multimeter, the LCD will display the startup message.
- Use the potentiomenter to select the desired measurement mode: voltage, current, resistance, or continuity.
- Adjust the scale using the pushbuttons as needed.
- Perform the measurement or continuity test, and the results will be displayed on the LCD.

## Customization

You can customize this DIY multimeter project in several ways:

- Modify the measurement ranges and scales to suit your specific requirements.
- Add additional features such as temperature measurement or capacitance measurement.
- Enhance the user interface by adding more buttons or implementing a graphical user interface (GUI).
- Incorporate calibration routines to improve measurement accuracy.

Feel free to experiment and tailor the project to meet your needs and preferences.

* Here is a circuit sketch done on TinkerCad [https://www.tinkercad.com/things/1GwrEckdTg0]
* Here is a detailed description of how the Arduino based multimeter works [https://docs.google.com/document/d/14qYNBZH344GmFOFm2AUpqamJqHqriOBdRsRI1oHYuVo/edit]
