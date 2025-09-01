# Pulse-Rate-Monitor
A simple pulse rate monitoring system using Arduino, a pulse sensor, and an LED indicator. It reads heartbeat signals, calculates BPM (beats per minute), and provides real-time feedback.
#  Heart Rate & SpO₂ Monitoring with ESP32 + MAX30100

##  Short Description
This project is a wearable health monitoring system that uses the **MAX30100 pulse oximeter sensor** and an **ESP32** microcontroller to measure **heart rate (BPM)** and **blood oxygen saturation (SpO₂)** in real time. The data is displayed via the serial monitor, and the system can be expanded for IoT/cloud-based health tracking.

---

##  Features
- Measures **heart rate (BPM)** in real-time  
- Calculates **SpO₂ (blood oxygen level)**  
- Uses an **LED indicator** for pulse detection feedback  
- Serial monitor output for live data  
- Can be extended to **mobile/IoT health platforms**

---

##  Components Used
**Hardware:**
- ESP32 Development Board  
- MAX30100 Pulse Oximeter Sensor  
- Jumper wires  
- Breadboard  
- LED (for pulse indication)  

**Software:**
- Arduino IDE  
- MAX30100 Library  
- ESP32 Board Package  

---

## ⚙ How It Works
1. The MAX30100 sensor emits light into the skin and detects reflection changes caused by blood flow.  
2. The ESP32 processes these signals to calculate heart rate and SpO₂.  
3. The data is displayed on the serial monitor in real-time.  
4. An LED blinks in sync with detected pulses for easy visualization.  

---

##  Author
**Master QAT**  
*Student | AI & Robotics Enthusiast | Future Robotics Engineer 🚀*  
