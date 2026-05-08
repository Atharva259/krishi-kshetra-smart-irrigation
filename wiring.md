# Wiring Explanation

## Krishi Kshetra Smart Irrigation System

The wiring architecture of the Krishi Kshetra Smart Irrigation System is designed to automate irrigation using soil moisture sensing and relay-controlled pump activation.

---

# Components Used

- Arduino / Microcontroller
- Soil Moisture Sensor
- Relay Module
- Water Pump
- LED Indicators
- Power Supply
- Jumper Wires

---

# Wiring Connections

## 1. Soil Moisture Sensor Connections

| Soil Sensor Pin | Arduino Connection |
|---|---|
| VCC | 5V |
| GND | GND |
| AO / Signal | Analog Pin (A0) |

### Purpose
The soil moisture sensor measures moisture levels in the soil and sends analog data to the microcontroller.

---

# 2. Relay Module Connections

| Relay Pin | Arduino Connection |
|---|---|
| VCC | 5V |
| GND | GND |
| IN | Digital Pin (D7 or configured pin) |

### Purpose
The relay acts as an electronic switch that controls the water pump based on sensor readings.

---

# 3. Water Pump Connections

| Pump Side | Connection |
|---|---|
| Positive | Relay NO Terminal |
| Negative | Power Supply Negative |

### Relay Terminal Connections

| Relay Terminal | Connection |
|---|---|
| COM | Power Supply Positive |
| NO | Pump Positive |

### Purpose
When soil moisture drops below the defined threshold, the relay activates and powers the pump automatically.

---

# 4. LED Indicator Connections

| LED Function | Arduino Pin |
|---|---|
| Pump Status LED | Digital Pin |
| System Status LED | Digital Pin |

### Purpose
LED indicators display:
- System active status
- Pump ON/OFF state
- Irrigation activity

---

# System Workflow

```text
Soil Moisture Sensor
        ↓
Arduino Reads Sensor Data
        ↓
Threshold Comparison
        ↓
Relay Activation
        ↓
Water Pump ON/OFF
        ↓
Automated Irrigation
```

---

# Safety Notes

- Ensure proper voltage compatibility
- Use external power supply for larger pumps
- Avoid direct high-current load on Arduino pins
- Keep wiring insulated and organized
- Test relay switching before continuous operation

---

# Future Improvements

- Wireless monitoring
- Cloud integration
- AI-based irrigation optimization
- Mobile application control
- Multi-zone irrigation support