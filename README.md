# Agrotech Lab Final Project - Seed counter 
Made by **Gali Shaani & Yonatan Schwartz**

------------------------------------------------------------------------------------------------------------------------

### Motivation:
Create a cheap alternative to the expensive machine " DATA COUNT S-25 PLUS Seed Counter " which costs around 8000$.
the system we offer costs around 150$ and has ___ correlation with the professional.


------------------------------------------------------------------------------------------------------------------------

### System Concept
The foundation of our system relies on a fixed ultrasonic distance sensor positioned at a constant distance from the wooden stick. When a seed passes the sensor, it detects a deviation from the static reading. We have determined that a disturbance (positive or negative) of 0.4 cm will be considered a seed. We established that a disturbance within a 0.3-second interval will be counted as a single seed to prevent multiple counts of the same seed.
To regulate the seed flow rate, we integrated a vibration motor into the system, connected to a power supply, allowing us to control the flow rate effectively. We programmed the system's features using Arduino [code](https://github.com/Yonatansch12/Agrotech-Lab-71252/blob/main/Code)









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
