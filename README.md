# Mouse A Sketch - A mouse with a _sketchy_ design

## Plan

Idea is simple enough - 2 rotary encoders, plugged into an RP2040 or AVR
ATMega32u4 which will send mouse instructions to a machine it's connected to.

BETTER! We could add an OLED, LCD or e-Ink/ePaper screen and make it actually do
sketching!

### Options

Digging through my screens I can see a few different options:
  - Mouse A Sketch Null
    - No screen as originally planned
  - Mouse A Sketch Nano
    - Use a 0.96" OLED I2C 128x64 display
  - Mouse A Sketch Micro
    - Use a 1.8" TFT 128x160 display
  - Mouse A Sketch Mini
    - Use a 2.8" TFT 240x320 display
  - Mouse A Sketch Mini 3
    - Use a 3.2" TFT 240x320 display
  - Mouse A Sketch Paper
    - Use a 7.5" e-Ink 640x384 display (5:3 == 1.66:1)

## About Etch A Sketch

### Overall size

The original classic Etch A Sketch body is apparently (citation - ? - some
random website) a size of 229mm x 187mm.

### Screen

The original classic Etch A Sketch apparently (citation - ? - some random
website) has a 159mm x 111mm "screen". This works out as a 193.91mm (7.63")
diagonal, with an aspect ratio of 1.43:1. None of the proposed screens match
this sort of ratio, though the eInk gets the closest at 1.66:1. It also ALMOST
matches the physical size AND it's e-Ink which looks most like an Etch A Sketch
- it was meant to be! :D

Based off various measurements I took from sourced photographs of the original
classic Itch A Sketch, from the bottom, the screen position is something
approximating 33.75mm, 37.93mm (left) and 197.28mm, 37.93mm.

### Knobs

Based off various measurements I took from sourced photographs of the original
classic Itch A Sketch, the knobs are as follows:

- Left knob:
  - Diameter: 29mm
  - Center position: 19.66mm, 174.49mm
- Right knob:
  - Diameter: 29mm
  - Center position: 212.94mm, 174.49mm

Unsure about height. Guessing 12mm perhaps.

----
[//]: # ( vim: set ts=4 sw=4 et cindent tw=80 ai si syn=markdown ft=markdown: )
