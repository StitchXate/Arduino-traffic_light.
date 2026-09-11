# Arduino Traffic Light

A simple Arduino traffic light simulation using red, yellow, and green LEDs with programmed timing.

## Overview

This project demonstrates a basic traffic light system using an Arduino and three LEDs. The lights automatically change in sequence using programmed delays.

## Components

- Arduino Uno
- Red LED
- Yellow LED
- Green LED
- Resistors
- Breadboard
- Jumper wires

## Pin Connections

| LED | Arduino Pin |
|-----|-------------|
| Red | 4 |
| Yellow | 3 |
| Green | 2 |

## How It Works

The Arduino controls three LEDs and changes them in a fixed sequence:

1. Green light stays on for 5 seconds.
2. Yellow light stays on for 2 seconds.
3. Red light stays on for 5 seconds.
4. The sequence repeats.

## What I Learned

- Using `pinMode()` and `digitalWrite()`
- Controlling LEDs with an Arduino
- Using [delay()] for timing
- Understanding basic Arduino programming and digital outputs

## Project Status

Completed beginner Arduino project.
