---
title: CP2112 USB-to-UART Bridge Board
author: sneakylizard123-4
description: USB-C breakout for the CP2112, with 1.8V
created_at: 2026-09-19
---

# September 19: Kickoff - schematic and PCB start

## What I did:

- started with usb-c with cc resistors
- Built the interface sheet around the CP2112
- Added a power sub-sheet for TLV75718PDBV 1.8V LDO
- Added the connector sub-sheet for 2x5 and 1x4 pin headers
- 8x status LEDs with 1k series resistors
- Created the PCB and started placement/routing (4-layer, 50 x 37.5 mm)

## Why:

- 50x37.5 is half of 50x75mm
- also probably cheaper than regular 50x75mm
- 1.8v just in case, so i can use it for 3.3v and 1.8v
- lots of leds for debugging

## Screenshots:

![schematic root sheet](images/CP2112.png)
![USB sub-sheet](images/CP2112-USB.png)

**Total time spent: 4 hours**

# September 20: Finishing the layout

## What I did:

- continued routing, cleanup before production export
- Generated production outputs
- Generated pcb renders
- generated cad model

## Why:

- <Why these final layout decisions>

## Screenshots:

![PCB render, top](images/pcb-render-top.png)
![PCB render, bottom](images/pcb-render-bottom.png)

**Total time spent: 4 hours**