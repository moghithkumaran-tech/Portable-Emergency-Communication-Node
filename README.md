# Portable Emergency Communication Node

## Overview
A battery-powered LoRa mesh communication system designed to provide reliable communication, GPS-based location sharing, and emergency coordination during disaster situations where conventional cellular networks are unavailable.

## Problem Statement
Communication networks often fail during natural disasters, making coordination, location tracking, and emergency response difficult. This project provides a decentralized communication system using LoRa technology, enabling real-time communication and GPS location sharing without relying on GSM or internet connectivity.

## Key Features
- LoRa-based long-range mesh communication
- GPS-based real-time location sharing
- Rescue team-to-team communication
- One-click SOS button for instant emergency alerts with live GPS location
- Offline mobile application for communication and monitoring
- Emergency message transmission
- Battery-powered portable device
- Operates without GSM or internet connectivity
- Low-power operation for extended field use

## Technologies Used

### Hardware
- ESP32
- LoRa Module
- GPS Module
- Push Button (SOS)
- Battery Management System
- Power Supply

### Software
- Arduino IDE
- Node.js
- HTML
- CSS
- JavaScript

## System Workflow

The workflow illustrates how each rescue node obtains its GPS location, exchanges messages and location information with nearby rescue teams through LoRa communication, sends SOS alerts with a single button press, and updates the offline mobile application with real-time information.

![System Workflow](workflow.png)

## System Flowchart

The flowchart illustrates the complete operation of the system, including system initialization, GPS location acquisition, LoRa network establishment, message transmission and reception, one-click SOS alert generation, GPS location sharing, and continuous communication between rescue teams through the offline mobile application.

![System Flowchart](flowchart.png)

## Results

Successfully established reliable long-range communication between multiple rescue teams, enabling real-time messaging, GPS-based location sharing, one-click SOS alerts, and offline communication without requiring cellular or internet connectivity.

## Future Scope

- Voice communication support
- Multimedia file sharing
- Drone-assisted search and rescue integration
- AI-based emergency response coordination
- Large-scale LoRa mesh network deployment
