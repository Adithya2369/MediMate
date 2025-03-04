# Medimate - Automatic Pill Dispenser

## Overview
Medimate is an IoT-based automatic pill dispenser designed to help individuals take their medications on time. The system integrates an ESP32 microcontroller with a servo motor and a circular disc mechanism to dispense pills at scheduled times. A web-based HTTPS interface allows users to set and manage their medication schedules.

## Features
- Automated pill dispensing based on preset schedules.
- ESP32 microcontroller for wireless connectivity and control.
- Web-based scheduling system for easy configuration.
- Reminder alerts to ensure timely medication.
- Simple and efficient pill loading and dispensing mechanism.

## Hardware Components
- ESP32 Microcontroller
- Servo Motor
- Circular Disc Mechanism
- Power Supply Module

## Software & Technologies
- ESP32 (Arduino/C++)
- Flask (Python)
- Firebase / Google Sheets API (for scheduling)
- HTTPS-based web interface
- Docker

## How It Works
1. User sets up a medication schedule via the web interface.
2. The schedule is stored in Firebase/Google Sheets.
3. ESP32 fetches the schedule and triggers the servo motor.
4. The motor rotates the disc to dispense the correct pills.
5. A notification is sent when pills are dispensed.

## Installation & Usage
1. Assemble the ESP32, servo motor, and disc mechanism.
2. Upload the firmware to ESP32.
3. Deploy the Flask server and connect to Firebase/Google Sheets.
4. Access the web interface to configure schedules.
5. The system will automatically dispense pills on time.
