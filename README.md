# Smart-Feeder--An-IoT-Based-Pet-Feeding-System
Blynk IoT to automate pet feeding with identity-based access via RFID. The system triggers a servo gate for registered pets, closing automatically. Users can manage pets, monitor feeding, and control the servo via the Blynk app with real-time alerts. It prevents unauthorized feeding and scales to 10 pets, with future AI/camera potential.
Component         Purpose
ESP8266(NodeMCU) - Main Microcontroller with WiFi
MFRC522 RFID     - User/Pet Authentication
HC-SR04 Ultrasonic - Food Level Monitoring
SG90 Servo Motor -  Mechanical Food Gate Actuator
Blynk IoT App    -  Remote Monitoring & Control 
HOW TO USE:
## 🛠️ Setup Instructions
1. Install the **Blynk Library** and **MFRC522 Library** in Arduino IDE.
2. Update the `WIFI_SSID` and `BLYNK_AUTH_TOKEN` in the firmware code.
3. Map **Virtual Pin V7** to a Button (Switch mode) in the Blynk App.
4. Map **Virtual Pin V20** to a Gauge (0-100) for Food Level.
5. Upload the code to your ESP8266.
