# RFID-car-parking-system-project

# 🚗 RFID-Based Car Parking System  

An IoT project using **ESP8266 + RFID RC522** for secure and automated vehicle parking access.  

##  Features  
- RFID-based access control  
- Servo motor to open/close parking gate  
- Buzzer alerts for unauthorized access  
- LCD/OLED display support for status messages  
- Easily customizable with multiple RFID cards  

##  Components  
- ESP8266 (NodeMCU)  
- RFID RC522 Module  
- Servo Motor (gate)  
- Buzzer  
- LCD/OLED Display (optional)  

##  How It Works  
1. The RFID reader scans the card/tag.  
2. If the UID matches the authorized list → **Gate opens**.  
3. If unauthorized → **Buzzer alert + access denied**.  
4. The system resets and waits for the next vehicle.  

---

 This project demonstrates how **RFID technology** can be applied to build a **secure, automated parking system**.  
