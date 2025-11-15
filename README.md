# 🌾 Smart Agricultural Pump Off-Timer System

A low-cost embedded system designed to **automatically control agricultural water pumps** based on a user-set timer.  
This project helps **protect irrigation pumps** from **dry running, overuse, and water drain-out**, improving **efficiency and safety** in rural farming applications.


## 🧩 Overview

Farmers often forget to turn off their pumps after irrigation, leading to **motor damage** and **water wastage**.  
This project provides a **programmable off-timer system** using an **Arduino Uno**, where the user can **set irrigation duration (hours and minutes)** using **potentiometers**.  

Once the preset time elapses, the **relay module** automatically cuts off the power supply to the pump.  
The system also stores the last set time in **EEPROM** and uses **hardware interrupts** for precise timing.

---

## ⚙️ Key Features

- ⏱ **Adjustable Timer:** Set irrigation time (hours and minutes) using potentiometers  
- 💾 **EEPROM Memory:** Retains the last-set time even after power loss  
- ⚡ **Interrupt-Driven Timer:** Ensures accurate countdown and non-blocking operation  
- 💡 **7-Segment Display:** Shows real-time countdown for easy monitoring  
- 🔌 **Relay Control:** Automatically switches off the pump after the timer expires  
- 🔋 **Reliable Power Design:** Operates efficiently on 5V DC supply  
- 🌿 **Rural-Friendly:** Simple, low-cost design ideal for farmers  



## 🛠️ Hardware Components

| Component | Description |

 **Arduino Uno** | Main controller to manage timing and control logic 
 **Potentiometers (2)** | Used to set irrigation duration (hours & minutes) 
 **7-Segment Display (4-digit)**  Displays countdown time 
 **Relay Module (5V)**  Controls the ON/OFF operation of the pump 
 **EEPROM   Stores the last set duration  
 **Power Supply**  5V DC (from adapter or regulated source) 



