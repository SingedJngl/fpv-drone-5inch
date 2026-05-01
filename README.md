# 5-Inch FPV Drone

## Overview
Design, assembly and configuration of a 5-inch freestyle FPV drone based on Betaflight.

## Objectives
- Build a reliable and maintainable FPV drone
- Optimize flight stability
- Configure the flight controller, ESC, radio receiver and VTX
- Understand PID tuning and filtering

## Hardware Used
| Component | Reference |
|----------|-----------|
| Frame | MotorRiot Tanq2 |
| Flight Controller | Mamba MK4 H743 V2 |
| ESC | Diatone 4in1 F55 128K |
| Motors | Velox V2207 V2 1750KV |
| FPV Camera | Foxeer T-Rex mini |
| Video Transmitter | SpeedyBee TX800 |
| Radio Receiver | RadioMaster Nano ELRS RP1 2.4 GHz V2 |
| Battery | LiPo Tattu 6S 1300 mAh |
| Buzzer | Vifly Finder 2 Autonomous Buzzer |

## System Architecture
LiPo Battery → 4-in-1 ESC → Motors  
Flight Controller → Radio Receiver / VTX / Camera / Buzzer

## Software Configuration
- Firmware: Betaflight
- ESC protocol: DShot 600
- Radio protocol: CRSF
- Flight modes: ACRO
- Failsafe configured

## Tuning
- PID tuning
- Gyro filters
- Rates
- OSD
- Blackbox

## Tests Performed
- Electrical continuity test
- Motor direction check
- Failsafe test
- First hover test
- Stability tests
- Filter/PID adjustments

## Issues Encountered
- Example: video noise
- Solutions implemented

## Results
- Final weight:
- Flight time:
- Flight behavior:
- Future improvements:

## Media
Add photos, wiring diagrams or videos here.
