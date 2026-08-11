<div align="center">

# 🌾 GREEN PULSE
### Modern Agricultural Monitoring and Management System

> 🏆 **National Science Exhibition Entry (2024–25)**  
> **Jawahar Navodaya Vidyalaya, Kollam (Hyderabad Region)**

An integrated, multi-node IoT agricultural ecosystem engineered to automate dynamic irrigation, secure field perimeters, monitor micro-climates, and detect aerial and subterranean crop threats.

---

</div>

##  Project Overview

**Green Pulse** addresses the critical demand for modern agricultural efficiency and water conservation. Developed using an multi-controller system (Arduino Uno & Mega microcontrollers), the project combines real-time sensor telemetry, automated actuation, and wireless communication to empower farmers with continuous field oversight.

The platform unifies **5 key operational subsystems** into a single cohesive smart farming network:
1. **Laser Perimeter Security:** Reflective laser boundary with automated SMS intrusion alerts.
2. **Ultrasonic Radar Tracking:** Servo-actuated radar sweep for bird monitoring and obstacle detection.
3. **Automated Irrigation Control:** Dynamic soil moisture telemetry paired with relay-operated pump control.
4. **Subterranean Burrow Detection:** Ground vibration sensing to protect root systems from burrowing animals.
5. **Environmental Climate Telemetry:** Ambient temperature and humidity tracking displayed on a real-time LCD.

---

##  Subsystem Specifications & Architecture

### 1.  Laser-Based Boundary Perimeter Security
* **Mechanism:** Uses a single laser diode positioned at one corner of the field, directed across strategically placed mirrors at the remaining three corners to create an unbroken reflective perimeter returning to a Light Dependent Resistor (LDR).
* **Alert Trigger:** Interruption of the continuous beam alters the LDR’s resistance, immediately firing a local audio buzzer and triggering a GSM module to send an automated SMS alert directly to the farmer.

### 2.  Radar for Bird Monitoring & Obstacle Avoidance
* **Mechanism:** An ultrasonic sensor is mounted on a 180° sweep servo motor to function as a localized radar scanner.
* **Echolocation Logic:** Continuously emits high-frequency sound waves and measures echo return latency to calculate obstacle distances, providing real-time alerts against birds and above-ground hazards.

### 3.  Soil Moisture & Automatic Irrigation System
* **Mechanism:** Sub-surface soil moisture sensors measure volumetric soil water content via electrical resistance/capacitance changes.
* **Automated Actuation:** When soil moisture drops below a calibrated threshold, the microcontroller signals a relay module to activate the water pump until optimal moisture equilibrium is restored, conserving water resources.

### 4.  Underground Burrow Detection System
* **Mechanism:** Ground disturbance sensors embedded slightly below soil level monitor soil vibrations caused by burrowing pests.
* **Alert Action:** Triggers audio alarms upon registering subterranean movement, offering early warnings before root structures suffer irreversible damage.

### 5.  Climate Monitoring & Real-Time Visualization
* **Telemetry:** Integrated temperature and humidity sensors continuously monitor environmental conditions.
* **Visualization:** Outputs real-time readings to a field-mounted 16x2 LCD display, enabling rapid on-site assessment.

---

##  Scientific Principles Applied

| System | Scientific Principle | Practical Application |
| :--- | :--- | :--- |
| **Laser Boundary** | *Electromagnetic Radiation & Optical Detection* | LDR resistance shift upon beam interruption. |
| **Obstacle Radar** | *Echolocation & Ultrasonic Wave Reflection* | Time-of-flight distance calculation via high-frequency audio pulses. |
| **Climate Sensing** | *Thermodynamics & Capacitive Hygrometry* | Thermal resistance variance & atmospheric moisture sensing. |
| **Auto-Irrigation** | *Soil Science & Electromechanical Relay Switching* | Moisture-dependent resistance variations triggering electromagnetic relays. |

---

##  Complete Bill of Materials (BOM)

| Component Name | Quantity | Function |
| :--- | :---: | :--- |
| **Arduino Uno Microcontroller** | 4 | Subsystem processing nodes |
| **Arduino Mega Microcontroller** | 1 | Central integration hub |
| **GSM Module (with SIM Card)** | 1 | Wireless SMS alert dispatching |
| **Ultrasonic Sensor (HC-SR04)** | 1 | Echolocation radar sweep |
| **Servo Motor** | 1 | 180° radar rotation actuator |
| **Laser Module + LDR** | 1 + 1 | Optical perimeter fence |
| **Soil Moisture Sensor** | 1 | Volumetric soil water sensing |
| **Relay Module + Water Pump** | 1 + 1 | Automated irrigation pump control |
| **Temperature & Humidity Sensor** | 1 | Atmospheric climate tracking |
| **LCD Module (16 x 2)** | 1 | Local real-time telemetry readout |
| **PIR Sensor & Buzzer** | 1 + 1 | Motion verification & acoustic alerts |

---

## 📄 Official Exhibition Documents

* 📄 **[View Full Project Write-Up (PDF)](./Green_Pulse_Writeup.pdf)**
* 🏆 **[View Official National Exhibition Certificate](./NVS_National_Certificate.pdf)**

---

##  Credits & Acknowledgments

* **Developer:** Master Jayakrishnan S (Class XI Science, JNV Kollam)
* **Project Guide (Chemistry):** Mr. Rajesh Kumar G (PGT Chemistry, JNV Kollam)
* **Project Guide (Physics):** Mr. R Revikumar (PGT Physics, JNV Kollam)
* **Institution:** Jawahar Navodaya Vidyalaya, Kollam (Principal & Science Faculty)