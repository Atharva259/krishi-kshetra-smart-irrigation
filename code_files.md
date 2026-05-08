# Code Files Structure

## Krishi Kshetra Smart Irrigation System

```text
krishi-kshetra-smart-irrigation/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── project-overview.md
│   ├── wiring-explanation.md
│   ├── future-roadmap.md
│
├── hardware/
│   ├── circuit-diagram.png
│   ├── components-list.md
│
├── code/
│   ├── irrigation_system.ino
│   ├── sensor_monitoring.ino
│   ├── relay_control.ino
│
├── assets/
│   ├── prototype-images/
│   ├── diagrams/
│
└── website/
    ├── frontend/
    ├── deployment-info.md
```

---

# Main Code Files

## 1. irrigation_system.ino

### Purpose
Main automation logic for the irrigation system.

### Responsibilities
- Read soil moisture data
- Compare moisture threshold
- Control relay activation
- Turn pump ON/OFF automatically
- Handle irrigation workflow

---

## 2. sensor_monitoring.ino

### Purpose
Sensor reading and monitoring module.

### Responsibilities
- Collect moisture sensor values
- Calibrate sensor readings
- Process analog input data
- Monitor environmental conditions

---

## 3. relay_control.ino

### Purpose
Relay switching and pump management.

### Responsibilities
- Activate relay
- Deactivate relay
- Control pump state
- Handle irrigation timing logic

---

# Documentation Files

## project-overview.md
Contains:
- Project summary
- Objectives
- Features
- Technology stack
- Workflow explanation

---

## wiring-explanation.md
Contains:
- Circuit connections
- Pin configuration
- Relay wiring
- Sensor integration
- System workflow

---

## future-roadmap.md
Contains:
- Development phases
- Future expansion plans
- AI integration goals
- Robotics roadmap

---

# Hardware Folder

## circuit-diagram.png
Contains:
- Wiring architecture
- Sensor connections
- Relay setup
- Pump control structure

---

## components-list.md
Contains:
- Hardware components
- Sensor details
- Power requirements
- Electronics overview

---

# Assets Folder

## prototype-images/
Stores:
- Prototype setup photos
- Hardware testing images
- Development snapshots

## diagrams/
Stores:
- System architecture diagrams
- Workflow visuals
- Technical illustrations

---

# Website Folder

## frontend/
Contains:
- Website source code
- UI structure
- Deployment configuration

## deployment-info.md
Contains:
- Hosting details
- Deployment instructions
- Website configuration

---

# Repository Purpose

The repository is designed to:
- Maintain technical documentation
- Track development progress
- Store embedded system code
- Support collaboration
- Showcase project architecture
- Present startup technical capabilities
