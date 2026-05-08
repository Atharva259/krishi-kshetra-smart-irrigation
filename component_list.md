# Components List

## Krishi Kshetra Smart Irrigation System

This document contains the hardware and electronic components used in the Krishi Kshetra Smart Irrigation System prototype.

---

# Core Components

| Component | Quantity | Purpose |
|---|---|---|
| Arduino Uno / Compatible Microcontroller | 1 | Main control unit |
| Soil Moisture Sensor | 1 | Detect soil moisture levels |
| Relay Module | 1 | Control water pump switching |
| Mini Water Pump | 1 | Irrigation water flow |
| Jumper Wires | Multiple | Electrical connections |
| Breadboard | 1 | Prototype circuit setup |
| LED Indicators | 2 | System and pump status indication |
| Resistors | As Required | LED current limiting |
| Power Supply | 1 | System power source |

---

# Sensor Components

## Soil Moisture Sensor

### Purpose
Measures soil moisture content and sends analog values to the microcontroller for irrigation control.

### Connections
- VCC → 5V
- GND → GND
- AO → Analog Input Pin

---

# Control Components

## Arduino / Microcontroller

### Purpose
Processes sensor data and controls automation logic.

### Responsibilities
- Read moisture levels
- Compare threshold values
- Activate/deactivate relay
- Manage irrigation workflow

---

## Relay Module

### Purpose
Acts as an electronic switch to safely control the water pump.

### Features
- Low-voltage trigger control
- Pump isolation
- Automatic switching

---

# Irrigation Components

## Water Pump

### Purpose
Supplies water during irrigation cycles.

### Operation
Activated automatically when soil moisture drops below the configured threshold.

---

# Indicator Components

## LED Indicators

### Functions
- System Status Indicator
- Pump Activity Indicator

### Purpose
Provide visual feedback for system operation and irrigation activity.

---

# Power Requirements

| Component | Voltage |
|---|---|
| Arduino | 5V |
| Soil Sensor | 3.3V / 5V |
| Relay Module | 5V |
| Water Pump | External Supply Recommended |

---

# Additional Optional Components

## Future Expansion Hardware

- Wi-Fi Module (ESP8266 / ESP32)
- LCD Display
- GSM Module
- Temperature Sensor
- Humidity Sensor
- Rain Sensor
- Battery Backup System
- Solar Power Module

---

# Prototype Notes

The current prototype is focused on:
- Irrigation automation
- Sensor integration
- Reliable relay control
- Scalable embedded architecture

The hardware configuration is designed to support future IoT and AI-based agricultural expansion.

---

# Future Hardware Goals

- Multi-zone irrigation control
- Wireless monitoring
- Smart agriculture analytics
- Autonomous farming systems
- AI-enabled crop monitoring
