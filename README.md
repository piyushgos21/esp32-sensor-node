# Project Name

Environmental & Motion Sensor Node

## Project Owner

**Name:** Piyush Goswami
**Virginia Tech Email:** piyushgos21@vt.edu

## Project Overview

This project is a custom two-layer PCB, designed in Altium Designer, for a small battery-powered sensor node. An ESP32-WROOM-32E module reads temperature, humidity and pressure from a BME280 and acceleration and rotation from an MPU6050. It shows live readings on an SSD1306 OLED and sends the data over Wi-Fi or Bluetooth LE. The board runs from USB-C or a 500 mAh LiPo cell, with onboard charging and 3.3 V regulation.

I'm building it for two reasons. It is my first complete PCB, so it gives me a chance to work through the whole flow from schematic to a board I can test. It also produces timestamped sensor data, which I want to use later to train a small motion-classification model for my machine learning minor. That model is outside the scope of this project; this repository only covers the hardware.

## What I Hope to Learn

- The full Altium Designer workflow: schematic capture, building and sourcing footprints, layout,     ERC and DRC, and generating manufacturing files.
- Power design for a portable board: LiPo charging, 3.3 V regulation, and choosing parts that can handle the ESP32's current peaks.
- Putting several I2C devices on one bus and bringing them up in firmware.
Structuring sensor output so it can be used for machine learning later.
Taking a design through fabrication, hand assembly, bring-up and debugging.

## Design and Implementation

Currently, schematic is in progress. 

## Bill of Materials

Document the major components and materials used for the project.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Component | 1 | $0.00 | Link |

**Estimated Total Cost:** $89.5

## Timeline and Milestones

Outline the major stages of the project and update them as work progresses.

| Milestone | Target Date | Status |
|---|---|---|
| Project planning | 2026-11-08 | In progress |
| Initial design (Schematic complete) | 2026-12-15 | Not Started |
| PCB Layout complete, boards ordered | 2027-1-15 | Not Started |
| Prototype | 2027-02-15 | Not Started |
| Testing and bring-up | 2027-03-01 | Not Started |
| Project Completiion | 2027-03-15 | Not Started |

## Progress Log


### YYYY-MM-DD

Describe what you worked on, what was completed, any problems you encountered, and what you plan to work on next.

## Project Files


## Useful Links


## Project Image

