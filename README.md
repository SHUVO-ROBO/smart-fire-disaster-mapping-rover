# smart-fire-disaster-mapping-rover

A low-cost IoT-based ESP32 robotic platform for fire and disaster-zone monitoring, survivor detection, environmental sensing, remote control, and live video surveillance.

## Overview

Smart Fire Disaster Mapping Rover is a low-cost IoT-based robotic first responder designed to enter fire-, smoke-, and gas-filled disaster zones before rescuers.

The rover provides remote mobility, environmental sensing, gas detection, human presence detection, and real-time video surveillance through Wi-Fi.

## Key Features

- Wi-Fi remote-controlled rover
- ESP32-based control system
- ESP32-S3 camera system
- Live video streaming
- Automatic video recording
- LD2410B human presence detection
- MQ-2 smoke/gas detection
- Temperature and humidity monitoring
- Real-time sensor dashboard
- Buzzer-based danger alert
- Remote web-based control
- Disaster-zone monitoring
- Rescuer safety support

## Hardware

- ESP32 DevKit
- ESP32-S3 CAM
- LD2410B
- MQ-2
- DHT22
- HC-SR04
- VL53L0X
- MPU6050
- BTS7960 motor drivers
- DC motors
- Servo motor
- Buzzer
- Battery system

## System Architecture

ESP32
→ Sensors
→ Motor Control
→ Web Dashboard

ESP32-S3 CAM
→ Live Video
→ Video Recording
→ Web Monitoring

## Project Structure

```text
ESP32/
└── Fire_Rescue_Rover_ESP32.ino

ESP32-S3-CAM/
└── Fire_Rescue_Rover_S3_CAM.ino
