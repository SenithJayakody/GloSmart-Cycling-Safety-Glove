# GloSmart — Smart Cycling Safety Glove

**A wearable embedded system for cyclist signaling and safety**

Undergraduate Project (2024)  
Department of Electrical and Electronic Engineering  
University of Peradeniya, Sri Lanka

## Overview

GloSmart is a smart cycling glove developed to improve cyclist visibility and safety through embedded sensing and wireless communication.

The system uses an ATmega328P microcontroller programmed in assembly language to interpret hand gestures and wirelessly control bicycle turn signals. It also incorporates GPS-based location tracking and GSM communication for collision-alert functionality.

The project was developed and completed as part of our undergraduate studies in Electrical and Electronic Engineering at the University of Peradeniya.

## Key Features

- **Gesture-Based Turn Signals:** Accelerometer-based recognition of cyclist hand gestures for turn-signal activation.
- **Wireless Communication:** nRF24L01 modules for communication between the wearable glove and bicycle lighting system.
- **Collision Alerts:** GPS and GSM integration for location-aware collision notification.
- **Low-Level Embedded Programming:** ATmega328P firmware developed using assembly language.

## Hardware and Technologies

| Component | Purpose |
|---|---|
| ATmega328P | Main microcontroller |
| Accelerometer | Hand-gesture and motion sensing |
| nRF24L01 | Wireless glove-to-bicycle communication |
| GPS Module | Location tracking |
| GSM Module | Collision-alert communication |
| Assembly Language | Microcontroller firmware development |

## Repository Status

**Project Status: Completed (2024)**

The hardware project was completed during undergraduate studies. The repository is being organized for public documentation and code sharing.

The following materials will be added as they become available:

- Assembly-language source code
- Circuit diagrams and hardware documentation
- Prototype photographs
- Additional implementation details

The repository does not yet contain a complete reproducible implementation.

## Project Context

This project demonstrates practical experience in embedded-system design, low-level programming, sensor integration, and wireless communication.

GloSmart was developed as an academic engineering prototype and is not a certified commercial bicycle safety device.

## Acknowledgments

Developed as a group undergraduate project at the Department of Electrical and Electronic Engineering, University of Peradeniya, Sri Lanka.

## License

Software released in this repository is licensed under the MIT License, subject to the rights of the respective contributors. See the [LICENSE](LICENSE) file. Hardware design files and third-party materials may have separate licensing terms.
