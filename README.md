# Pintell – Smart Laundry Moisture Monitor

<p align="left">
  <img src="pintell_photo.jpg" alt="Pintell Final Product" width="300"/>
</p>

**Course:** ELEC-C9822 – Design Thinking and Advanced Prototyping (10 credits)  
**Purpose:** Pintell is designed to monitor your laundry's moisture levels in real-time, letting you know exactly when your clothes are dry. It saves time and energy compared to using dryers, relying on the weather, or checking manually.
**Note:** Unlike a traditional clothespin, Pintell’s primary focus is **accurate moisture monitoring**, not holding clothes in place. For best results, clip it to the *bottom* of the garment: moisture naturally moves downward as clothes dry, and the bottom retains moisture the longest. The **core functionality of Pintell is precise real-time moisture data**, even though the form is inspired by the familiar clothespin.

---

## System Overview
Pintell combines smart electronics, embedded programming, and cloud connectivity to deliver actionable laundry insights:

- **Electronics:** Sensors detect moisture levels accurately; PCB and power management ensure durability and efficiency.
- **Embedded Programming:** Microcontroller firmware processes sensor data and communicates with the app.
- **Cloud Services:** Real-time data storage and analysis for user notifications.
- **Mobile App:** Displays moisture readings and sends alerts when laundry is dry.

---

## Hardware Overview (My Role)
**Petteri Suonpää – Electronics Engineering**  
As part of ELEC-C9822 - Design Thinking and Advanced Prototyping (10 credits), I was responsible for designing and developing the electronic system for Pintell. Key highlights of my work include:

- **Moisture Sensor:** Researched, selected, and integrated a high-accuracy sensor at the bottom of the garment for precise real-time readings.  
- **PCB Design & Prototyping:** Designed custom 1-2 layer PCBs in KiCad. I milled a prototype PCB in the lab for testing, refined the design based on results, and ordered the final version from JLCPCB.  
- **Power Management:** Developed an efficient battery system to ensure extended usage between charges.  
- **Connectivity:** Programmed the microcontroller to handle sensor data and transmit it to the mobile app.  
- **Testing & Validation:** Verified sensor functionality, PCB performance, and overall system reliability, iteratively refining the design as needed.  

### Hardware Photos
1. **PCB & Electronics Assembly**  
[📄 Pintell Design Report (PDF)](Kicad_layout.pdf)  

2. **Sensor Integration Close-up**  
![Sensor Close-up](images/sensor_closeup.jpg)  

3. **Final Product in Use**  
![Pintell on Garment](images/in_use.jpg)

---

## Team Members & Roles
- **Vu Minh, Nguyen** – Cloud Service Programming  
- **Khanh, Pham** – App Programming (Project Manager)  
- **Petteri, Suonpää – Electronics Engineering** ✅  
- **Julius, Lappalainen** – Embedded Programming  
- **Aykhan, Najafov** – User Experience and Interaction Design  
- **Duc Anh, Pham** – Physical Design  

---

## Features
- Real-time moisture monitoring  
- Notifications when laundry is dry  
- Efficient power usage for prolonged battery life  
- Easy-to-clip design inspired by a clothespin  

---

## Usage
1. Clip Pintell to the **bottom of a garment**.  
2. Turn the device on; it will automatically detect moisture levels.  
3. Connect to the mobile app to monitor progress in real-time.  
4. Receive alerts when the garment is dry and ready.  

---
