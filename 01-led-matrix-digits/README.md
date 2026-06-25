# LED Matrix Digits

This is my first Arduino UNO R4 WiFi LED matrix project.

## Goal

Display the digits `0` and `1` alternately on the built-in 12x8 LED matrix.

## Hardware

- Arduino UNO R4 WiFi
- Built-in LED Matrix

## What I learned

- `setup()` runs once when the board starts.
- `loop()` runs repeatedly.
- `matrix.begin()` initializes the LED matrix.
- `matrix.renderBitmap()` displays a bitmap on the LED matrix.
- A digit can be represented by an 8x12 array of `0`s and `1`s.

## Behavior

The program displays:

1. `0` for one second
2. `1` for one second
3. repeats forever

## Code idea

Each digit is stored as a bitmap:

- `1` means the LED is on
- `0` means the LED is off
