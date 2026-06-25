# Arduino Learning

This repository records my process of learning Arduino and embedded systems through small hands-on projects.

I am starting with an Arduino UNO R4 WiFi board and using simple experiments to understand how hardware and software interact.

## Goals

* Learn the basics of Arduino programming
* Understand common embedded systems concepts
* Practice writing clean and readable C/C++ code
* Build small hardware projects step by step
* Document what I learn along the way

## Hardware

Current board:

* Arduino UNO R4 WiFi

## Topics I am learning

* Digital output
* Digital input
* LED matrix display
* Buttons and switches
* Analog input
* PWM
* Serial communication
* Sensors
* I2C / SPI / UART basics
* Embedded C/C++ programming

## Project List

| Project                | Description                               | Status      |
| ---------------------- | ----------------------------------------- | ----------- |
| `01-led-matrix-digits` | Display digits on the built-in LED matrix | In progress |

## Repository Structure

```text
arduino-learning/
├── README.md
└── 01-led-matrix-digits/
    ├── 01-led-matrix-digits.ino
    └── README.md
```

Each project folder contains:

* Arduino sketch code
* A short README explaining the goal, hardware, and what I learned

## Notes

This is a learning journal, not a polished product repository.
The goal is to record experiments, mistakes, fixes, and progress honestly.

## First Project

The first project uses the built-in 12x8 LED matrix on the Arduino UNO R4 WiFi to display digits `0` and `1` alternately.

Through this project, I learned:

* `setup()` runs once when the board starts
* `loop()` runs repeatedly
* `void` means a function does not return a value
* `matrix.begin()` initializes the LED matrix
* `matrix.renderBitmap()` displays a bitmap pattern
* A digit can be represented by an array of `0`s and `1`s
