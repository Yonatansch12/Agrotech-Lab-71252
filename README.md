# Agrotech Lab Final Project - Seed counter 
Made by **Gali Shaani & Yonatan Schwartz**

------------------------------------------------------------------------------------------------------------------------

### Motivation:
Create a cheap alternative to the expensive machine " DATA COUNT S-25 PLUS Seed Counter " which costs around 8000$.
the system we offer costs around 150$ and has a 70-95% correlation with the professional.


------------------------------------------------------------------------------------------------------------------------

### System Concept
The foundation of our system relies on a fixed ultrasonic distance sensor positioned at a constant distance from the wooden stick. When a seed passes the sensor, it detects a deviation from the static reading. We have determined that a disturbance (positive or negative) of 0.4 cm will be considered a seed. We established that a disturbance within a 0.3-second interval will be counted as a single seed to prevent multiple counts of the same seed.
To regulate the seed flow rate, we integrated a vibration motor into the system, connected to a power supply, allowing us to control the flow rate effectively. We programmed the system's features using Arduino [code](https://github.com/Yonatansch12/Agrotech-Lab-71252/blob/main/Code). 
The system includes an OLED screen that displays the counting progress.

During the project, we measured the success rate of seed counting across different prototypes. The system’s success rate ranged from 70% to 92%, with the final prototype achieving the highest success rate of 92%.

------------------------------------------------------------------------------------------------------------------------
## Hardware
#### Electronic Compoenets: 
- FireBeetle 2 ESP-32 E
- Arduino Nano
- Breadboard
- Power supply
- HC-SR04 Ultrasonic sensor
- VL53L0 laser sensor
- OLED display
- Switch
- Jump wires 


#### Supporting Components: 
- Chassis
- Seed funnel
- Seed slide with bottleneck
- Acoustic tube
- Seed container
- Wooden sticks for structural support
  
------------------------------------------------------------------------------------------------------------------------
### improvement suggestions
To improve our system, we propose several methods that target different components of the system:
1. Higher-quality sensors: More precise laser sensors, IR sensors, or multiple sensors can ensure only one seed is counted at a time.
2. Enhancing the system's ability to control seed flow and optimize it according to the sensor's operating rate.
3. Improving the quality of materials used: lightweight metals, high-quality plastics, and a better and stronger overall framework.
4. To integrate the capability into the system to send data and counts to a web interface with easy access, which also stores the data history, you could consider using Wi-Fi or Bluetooth modules like the ESP8266 or ESP32. These modules can connect to a server or cloud service, allowing real-time data logging and easy access from any device with internet connectivity.

