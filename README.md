# RP2040 Minimal Project for KiCad

This repository contains a modified version of the Raspberry Pi RP2040 Minimal design.

The modified version is more suited to recent KiCad versions (for instance KiCad 10), and it improves things slightly if the board is to be produced, for fewer 0402 parts rotating/sliding/tombstoning issues.

## Schematic

The schematic includes the RP2040 microcontroller along with supporting circuitry: a 3.3V regulator (NCP1117), W25Q128JVS flash memory, an ABM8 crystal oscillator, a GCT USB4085 USB-C connector with ESD protection, BOOTSEL and RESET buttons, an LED indicator, and a SWD debug port.

![Schematic](doc/rp2040-min-board-schematic.png)

## PCB Layout

The PCB layout shows the top copper layer of the board. Key components are clearly labelled, including the RP2040, flash (U2), 3.3V regulator (U1), USB-C connector, BOOTSEL and RESET switches, crystal (X1), and the DEBUG header.

![PCB Layout](doc/rp2040-min-board-top.png)

## 3D Render

The 3D render provides a view of the assembled board, showing the physical placement of all components including the USB-C connector, tactile switches, LED, crystal, and the SWD debug header.

![3D Render](doc/rp2040-min-board-render.png)

