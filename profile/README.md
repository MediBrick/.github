<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

# MediBrick

MediBrick develops open-source biomedical sensor hardware and software,
with a focus on modular sensor boards, firmware, and data acquisition
tools.

## MediBrick Overview

Project Overview and Definition: [Git](https://github.com/MediBrick/MediBrick)
Education Content: 📖, 
Sources used to determine a solution: ✔, 
Solution: 📂, 
Assembly Instructions: 🛠, 
Software: 📈

## 📟 **Bricks** – Reference hardware designs and manufacturing instructions for MediBricks
- ECG & Impedance: [↳Git](https://github.com/MediBrick/ECG_BIOZ_Brick)
- Pulse Oximeter: [↳Git](https://github.com/MediBrick/SPO2_Brick)
- Electronic Stehthoscope and Blood Pressuce: [↳Git](https://github.com/MediBrick/Stethoscope_BP_Brick)
- Temperature: [↳Git](https://github.com/MediBrick/Thermistor_Brick)
- Activity: [↳Git](https://github.com/MediBrick/IMU_Brick)
- Airquality: [↳Git](https://github.com/MediBrick/Airquality_Brick)
- Spirometer: [↳Git](https://github.com/MediBrick/Airflow_Brick)
- DC Power Controller: [↳Git](https://github.com/MediBrick/DC_Power_Brick)
- Heater-Cooler Controller: [↳Git](https://github.com/MediBrick/HeaterCooler_Brick)
- BLDC Controller (future): [✗Git]()
- Mouse Monitor (future): [↳Git](https://github.com/MediBrick/Mouse_Brick)

## Software 
Original Software created for MediBrick.

### 🔌 **Data Display and Recording** 
Main program to interact with MediBricks
- [SerialUI](https://github.com/uutzinger/SerialUI) Terminal program to connect to MediBrick devices via USB and Bluetooth

### 🔌 **Firmware** 
Arduino libraries created for MediBricks
  - [↗AFE44XX](https://github.com/uutzinger/Arduino_AFE44XX) SPO2 Brick
  - [↗MAX3001G](https://github.com/uutzinger/Arduino_MAX30001G), ECG&BIOZ Brick
  - [↗DRV8704](https://github.com/uutzinger/Arduino_DRV8704), DC controller

### 🧰 **Tools**
General Arduino libraries
- [↗BLE Serial](https://github.com/uutzinger/Arduino_BLESerial), Serial communicaiton using Nordic UART for ESP
- [↗RingBuffer](https://github.com/uutzinger/Arduino_RingBuffer), Ringbuffer for microcontrollers
- [↗SG Filter](https://github.com/uutzinger/SavitzkyGolayFilter), Savitzky Golay Signal Filter

### 📋 **Test** 
Software to test individual components on a MediBrick

## Contributing
We welcome contributions! We use [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to create and change documentation.
