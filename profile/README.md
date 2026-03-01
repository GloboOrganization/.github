# 🚀 PiccardNode  
**Experimental High-Altitude Balloon with LoRa Telemetry and Real-Time Ground Control**

PiccardNode is an experimental high-altitude balloon (HAB) project designed to reach the stratosphere (25–30 km), transmit real-time telemetry via LoRa, recover the payload, and analyse atmospheric data post-flight.

The project integrates embedded systems, RF communications, trajectory simulation, and a custom ground control station.

---

## 🌍 Project Overview

The mission consists of:

- Stratospheric balloon flight (25–30 km altitude)
- Real-time telemetry transmission (LoRa 868 MHz)
- Onboard data logging
- GPS tracking and recovery
- Ground control station with live map and trajectory prediction
- Post-flight data analysis and documentation

---

## 🧠 System Architecture

### Air Segment (Payload)

- Microcontroller (MCU)
- LoRa transceiver
- GNSS receiver
- Environmental sensors (Temperature, Pressure, Humidity)
- Optional camera
- Data logging (SD / Flash)
- Battery + power regulation
- Thermal insulation enclosure

### Ground Segment

- LoRa receiver
- Laptop-based ground control station
- Local WiFi server
- Mobile interface for live tracking
- Trajectory simulation engine

---

## 📡 Telemetry

Data transmitted during flight:

- Latitude / Longitude
- Altitude
- Vertical speed
- Temperature
- Pressure
- Battery level
- Link quality (RSSI / SNR)

Telemetry packets are designed for:

- Low bandwidth
- Robust transmission
- Optional encryption (AES-based)

---

## 📊 Flight Profile

Typical mission sequence:

1. Pre-flight trajectory simulation
2. Launch
3. Ascent (~5–6 m/s)
4. Burst altitude (~25–30 km)
5. Descent with parachute
6. Landing detection
7. Recovery
8. Data extraction and analysis

---

## 🧪 Development Phases

1. Regulatory research and compliance  
2. System definition and requirements  
3. COTS prototype  
4. Firmware development  
5. Custom PCB integration  
6. Environmental testing (cold, vibration, range)  
7. Ground station development  
8. Flight execution  
9. Data analysis and publication  

---

## 🛠 Repository Structure
/firmware → Payload embedded code
/hardware → Schematics and PCB designs
/ground-station → Ground control software
/simulation → Trajectory simulation tools
/docs → Documentation and reports
/tests → Environmental and range testing
/media → Photos and flight results


---

## 📐 Technical Objectives

- Payload mass < 4 kg (regulatory compliance)
- Operational down to –60°C external temperature
- Flight duration: 2–3 hours
- Communication range: > 50 km (line of sight)
- Full payload recovery

---

## ⚖ Legal & Safety

The system is designed to comply with:

- EU unmanned free balloon regulations
- Weight limits for light category
- Prior notification to air traffic authorities
- Use of ISM band (868 MHz) within legal limits

---

## 🎯 Goals

- Demonstrate end-to-end embedded system design
- Validate near-space telemetry performance
- Develop real-time landing prediction
- Publish technical findings
- Open-source the architecture

---

## 📸 Results (To Be Updated After Flight)

- Maximum altitude:  
- Flight duration:  
- Distance travelled:  
- Landing coordinates:  
- Data plots and analysis:  

---

## 👤 Author

Developed as an independent experimental aerospace and embedded systems project.
