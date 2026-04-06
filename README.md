# RF & Electronic Symbols for draw.io / diagrams.net

A curated SVG symbol library for **RF, microwave, control, embedded, networking, and electronic filter schematics**, designed for easy use in **draw.io / diagrams.net**.

This repository contains reusable vector symbols for building clean technical diagrams such as:

- RF front-end block diagrams
- radar architectures
- microwave chains
- embedded control systems
- networking and data-flow diagrams
- filter and instrumentation schematics

All symbols are provided as **SVG files** and as **draw.io custom library XML files** for quick import.

---

## Overview

This project was created to simplify the process of drawing professional RF and electronics schematics in draw.io.  
Instead of redrawing the same blocks repeatedly, this library provides a consistent set of reusable symbols covering:

- antennas
- RF components
- connectors and adapters
- beamforming devices
- embedded platforms
- computing/software blocks
- networking symbols
- electronic filter symbols

The goal is to keep the symbols:

- visually consistent
- easy to search
- simple to import
- practical for engineering diagrams

---

## Features

- **SVG-based symbols** for crisp scaling at any size
- **draw.io / diagrams.net library XML** for direct import
- symbols for **RF, microwave, embedded, network, and software systems**
- support for **connector variants**, including **90° versions**
- custom blocks for specific devices such as the **ADAR1000**
- electronic filter symbols based on the supplied reference set
- organized naming for easier reuse in large projects

---

## Included Symbol Categories

### RF / Microwave
- antenna
- dipole antenna
- monopole antenna
- waveguide horn antenna
- microstrip antenna / patch antenna
- loop antenna
- helical antenna
- array antenna
- AESA antenna
- LNA
- PA
- attenuator
- phase shifter
- mixer
- LO
- SPDT switch
- directional coupler
- splitter / divider
- combiner
- circulator
- isolator
- balun
- duplexer
- detector
- log power detector
- transmission line
- waveguide
- terminator

### Connectors / Adapters
- SMA male / female
- SMA male-male
- SMA female-female
- SMA male-female
- N-type male / female
- coax connector
- waveguide-to-coax adapter
- 2.92 mm to 1.85 mm coax adapter
- multiple **90° connector and adapter variants**

### Embedded / Control / Digital
- microcontroller
- ADC
- FPGA
- USB interface
- Raspberry Pi
- Arduino
- LattePanda
- motor
- motor driver

### Networking / Systems
- ethernet cable
- switch
- router
- Wi-Fi antenna
- desktop
- cloud
- database

### Software / Workflow
- MATLAB
- MATLAB plot
- Python
- Django
- Web API
- Notebook

### Electronic Filter Symbols
- general filter
- high-pass filter
- low-pass filter
- band-pass filter
- band-stop filter
- band-pass filter switched by gas discharge
- mode filter
- surface acoustic wave (SAW) filter
- band-pass filter with variable pass-band
- band-pass filter with variable centre frequency
- variable band-stop filter

### Custom / Device-Specific
- ADAR1000 beamformer symbol
- 4-input / 1-output combiner block

---

## Repository Structure

Example structure:

```text
.
├── rf_symbols_drawio_v7/
│   ├── *.svg
│   ├── RF_Symbols_DrawIO_Library_v7.xml
│   └── preview_sheet_v7_addition.png
├── electronic_filter_symbols_svg/
│   ├── *.svg
│   ├── Electronic_Filter_Symbols_DrawIO_Library.xml
│   └── preview_sheet.png
├── *.zip
└── README.md
