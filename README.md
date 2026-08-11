<div align="center">

# 🌾 GREEN PULSE
### Modern Agricultural Monitoring and Management System

> 🏆 **National Science Exhibition Entry (2024–25)**[cite: 1]  
> **Jawahar Navodaya Vidyalaya, Kollam (Hyderabad Region)**[cite: 1]

An integrated, multi-node IoT agricultural ecosystem engineered to automate dynamic irrigation, secure field perimeters, monitor micro-climates, and detect aerial and subterranean crop threats[cite: 1].

---

</div>

##  Project Overview

**Green Pulse** addresses the critical demand for modern agricultural efficiency and water conservation[cite: 1]. Developed using an multi-controller system (Arduino Uno & Mega microcontrollers)[cite: 1], the project combines real-time sensor telemetry, automated actuation, and wireless communication to empower farmers with continuous field oversight[cite: 1].

The platform unifies **5 key operational subsystems** into a single cohesive smart farming network[cite: 1]:
1. **Laser Perimeter Security:** Reflective laser boundary with automated SMS intrusion alerts[cite: 1].
2. **Ultrasonic Radar Tracking:** Servo-actuated radar sweep for bird monitoring and obstacle detection[cite: 1].
3. **Automated Irrigation Control:** Dynamic soil moisture telemetry paired with relay-operated pump control[cite: 1].
4. **Subterranean Burrow Detection:** Ground vibration sensing to protect root systems from burrowing animals[cite: 1].
5. **Environmental Climate Telemetry:** Ambient temperature and humidity tracking displayed on a real-time LCD[cite: 1].

---

##  Subsystem Specifications & Architecture

### 1.  Laser-Based Boundary Perimeter Security
* **Mechanism:** Uses a single laser diode positioned at one corner of the field, directed across strategically placed mirrors at the remaining three corners to create an unbroken reflective perimeter returning to a Light Dependent Resistor (LDR)[cite: 1].
* **Alert Trigger:** Interruption of the continuous beam alters the LDR’s resistance[cite: 1], immediately firing a local audio buzzer and triggering a GSM module to send an automated SMS alert directly to the farmer[cite: 1].

### 2.  Radar for Bird Monitoring & Obstacle Avoidance
* **Mechanism:** An ultrasonic sensor is mounted on a 180° sweep servo motor to function as a localized radar scanner[cite: 1].
* **Echolocation Logic:** Continuously emits high-frequency sound waves and measures echo return latency to calculate obstacle distances, providing real-time alerts against birds and above-ground hazards[cite: 1].

### 3.  Soil Moisture & Automatic Irrigation System
* **Mechanism:** Sub-surface soil moisture sensors measure volumetric soil water content via electrical resistance/capacitance changes[cite: 1].
* **Automated Actuation:** When soil moisture drops below a calibrated threshold, the microcontroller signals a relay module to activate the water pump until optimal moisture equilibrium is restored, conserving water resources[cite: 1].

### 4.  Underground Burrow Detection System
* **Mechanism:** Ground disturbance sensors embedded slightly below soil level monitor soil vibrations caused by burrowing pests[cite: 1].
* **Alert Action:** Triggers audio alarms upon registering subterranean movement, offering early warnings before root structures suffer irreversible damage[cite: 1].

### 5.  Climate Monitoring & Real-Time Visualization
* **Telemetry:** Integrated temperature and humidity sensors continuously monitor environmental conditions[cite: 1].
* **Visualization:** Outputs real-time readings to a field-mounted 16x2 LCD display, enabling rapid on-site assessment[cite: 1].

---

##  Scientific Principles Applied

| System | Scientific Principle | Practical Application |
| :--- | :--- | :--- |
| **Laser Boundary** | *Electromagnetic Radiation & Optical Detection*[cite: 1] | LDR resistance shift upon beam interruption[cite: 1]. |
| **Obstacle Radar** | *Echolocation & Ultrasonic Wave Reflection*[cite: 1] | Time-of-flight distance calculation via high-frequency audio pulses[cite: 1]. |
| **Climate Sensing** | *Thermodynamics & Capacitive Hygrometry*[cite: 1] | Thermal resistance variance & atmospheric moisture sensing[cite: 1]. |
| **Auto-Irrigation** | *Soil Science & Electromechanical Relay Switching*[cite: 1] | Moisture-dependent resistance variations triggering electromagnetic relays[cite: 1]. |

---

##  Complete Bill of Materials (BOM)

| Component Name | Quantity | Function |
| :--- | :---: | :--- |
| **Arduino Uno Microcontroller** | 4[cite: 1] | Subsystem processing nodes[cite: 1] |
| **Arduino Mega Microcontroller** | 1[cite: 1] | Central integration hub[cite: 1] |
| **GSM Module (with SIM Card)** | 1[cite: 1] | Wireless SMS alert dispatching[cite: 1] |
| **Ultrasonic Sensor (HC-SR04)** | 1[cite: 1] | Echolocation radar sweep[cite: 1] |
| **Servo Motor** | 1[cite: 1] | 180° radar rotation actuator[cite: 1] |
| **Laser Module + LDR** | 1 + 1[cite: 1] | Optical perimeter fence[cite: 1] |
| **Soil Moisture Sensor** | 1[cite: 1] | Volumetric soil water sensing[cite: 1] |
| **Relay Module + Water Pump** | 1 + 1[cite: 1] | Automated irrigation pump control[cite: 1] |
| **Temperature & Humidity Sensor** | 1[cite: 1] | Atmospheric climate tracking[cite: 1] |
| **LCD Module (16 x 2)** | 1[cite: 1] | Local real-time telemetry readout[cite: 1] |
| **PIR Sensor & Buzzer** | 1 + 1[cite: 1] | Motion verification & acoustic alerts[cite: 1] |

---

## 📄 Official Exhibition Documents

* 📄 **[View Full Project Write-Up (PDF)](./Green_Pulse_Writeup.pdf)**[cite: 1]
* 🏆 **[View Official National Exhibition Certificate](./NVS_National_Certificate.pdf)**[cite: 1]

---

##  Credits & Acknowledgments

* **Developer:** Master Jayakrishnan S (Class XI Science, JNV Kollam)[cite: 1]
* **Project Guide (Chemistry):** Mr. Rajesh Kumar G (PGT Chemistry, JNV Kollam)[cite: 1]
* **Project Guide (Physics):** Mr. R Revikumar (PGT Physics, JNV Kollam)[cite: 1]
* **Institution:** Jawahar Navodaya Vidyalaya, Kollam (Principal & Science Faculty)[cite: 1]