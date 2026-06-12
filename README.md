# 🌱 CropMitra – IoT-Based Smart Irrigation System
CropMitra is an IoT-powered irrigation solution designed to help farmers optimize water usage, automate irrigation, and boost crop productivity. By integrating soil and weather sensors with real-time monitoring, the system ensures efficient water management and supports sustainable agriculture.


## 📘 Project Summary
CropMitra combines IoT, sensors, and automation to track soil moisture and weather conditions. Using this data, it makes intelligent irrigation decisions, reducing water wastage and improving crop yield.
The system is built around a NodeMCU ESP8266 microcontroller, which collects soil and environmental data and controls a water pump via a relay. A web dashboard (HTML, CSS, JavaScript) provides farmers with live updates and remote monitoring capabilities.


## 🧠 Key Features
🌾 Automated Irrigation – Pump activates when soil is dry.

☁️ Weather-Aware Scheduling – Adjusts irrigation if rainfall or high humidity is detected.

📶 IoT Connectivity – Real-time updates via Wi-Fi.

📊 Web Dashboard – Interactive charts for soil and climate data.

🔔 Alerts & Notifications – Moisture and irrigation status updates.

⚙️ Customizable Thresholds – Farmers can set moisture/temperature limits.

🌍 Eco-Friendly – Promotes water conservation and sustainable farming.


## 🧩 System Components
#### Hardware:

NodeMCU ESP8266

Soil Moisture Sensor

DHT11 Sensor (Temperature & Humidity)

Relay Module

DC Water Pump

Breadboard, Jumper Wires, Power Supply

#### Software:

Arduino IDE

HTML, CSS, JavaScript (Web Interface)

Figma (UI Design)

## ⚙️ Working Principle
Soil moisture sensor measures humidity levels.

ESP8266 processes data and decides irrigation need.

Relay triggers pump if soil is dry.

Pump stops once optimal moisture is reached.

DHT11 sensor adjusts logic based on temperature/humidity.

Data is displayed on the web dashboard in real time.


## 🌐 Web Application
Login/Signup – Secure user access.

Dashboard – Real-time soil, temperature, and pump status.

Summary Page – Crop-specific ideal conditions.


## 💻 Example Code

if (moisture > MOISTURE_THRESHOLD_DRY) {

    digitalWrite(RELAY_PIN, HIGH); // Pump ON
    Serial.println("Soil is dry – irrigation started");
} else {

    digitalWrite(RELAY_PIN, LOW);  // Pump OFF
    Serial.println("Moisture optimal – irrigation stopped");
}


## 🧾 Conclusion
CropMitra is a cost-effective, scalable solution for smart farming. By merging IoT and automation, it enhances water efficiency, improves crop yield, and supports sustainable agriculture.


## 🔗 References
IEEE – IoT Smart Irrigation

ResearchGate – Precision Agriculture

MDPI – Smart Agriculture Sensors

IOP Science – Smart Irrigation Architecture


## 🛠️ Future Enhancements
Mobile app notifications

Solar-powered independence

Machine learning for predictive irrigation

Database & analytics dashboards

Crop disease detection with solutions


**👨‍💻 Team Members**
K. Sri Harsha – 24R05A0524

M. Navya – 24R05A0527

M. Lokesh – 24R05A0530

P. Navyasri – 24R05A0535

**🎓 Institution**
CMR Institute of Technology (UGC Autonomous)  
Approved by AICTE | Affiliated to JNTUH | Accredited by NBA & NAAC
Kandlakoya (V), Medchal District – 501401
www.cmrithyderabad.edu.in


