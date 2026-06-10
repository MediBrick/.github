<!--
Medi Brick
-->

# MediBrick

MediBrick develops open-source biomedical sensor hardware and software, with a focus on modular sensor boards, firmware, and data acquisition tools. This project also provides education content.

Please read the [Project Overview ↳Git 📂](https://github.com/MediBrick/MediBrick). It describes all activities related to MediBrick.

Links to repositories in the project: ↳Git 📂

Links to affiliated repositories: ↗Git 📂

## 📟 **Bricks** 
Reference hardware designs and manufacturing instructions for MediBricks
- ECG & Impedance: [↳Git 📂](https://github.com/MediBrick/ECG_BIOZ_Brick) MAX30001G
- Pulse Oximeter: [↳Git 📂](https://github.com/MediBrick/SPO2_Brick) AFE4400
- Electronic Stehthoscope and Blood Pressuce: [↳Git](https://github.com/MediBrick/Stethoscope_BP_Brick) ES8388, MPRLS0300YG
- Temperature: [↳Git 📂](https://github.com/MediBrick/Thermistor_Brick), 10k Thermistors
- Activity: [↳Git 📂](https://github.com/MediBrick/IMU_Brick), ICM20948, BMP581
- Airquality: [↳Git 📂](https://github.com/MediBrick/Airquality_Brick), SEN50, SCD40, SHT45, BMP581, SGP41, MiCS-6814 
- Spirometer: [↳Git 📂](https://github.com/MediBrick/Airflow_Brick), SFM3300
- DC Power Controller: [↳Git 📂](https://github.com/MediBrick/DC_Power_Brick), DRV8704, CSD18540Q5B
- Heater-Cooler Controller: [↳Git 📂](https://github.com/MediBrick/HeaterCooler_Brick), IR2113, IRF3205
- BLDC Controller (future): [✗Git 📂]()
- Mouse Monitor (future): [↳Git 📂](https://github.com/MediBrick/Mouse_Brick)

## </> Software 
Original Software created for MediBrick.

### 📈 **Data Display and Recording** 
Main program to interact with MediBricks:
- [SerialUI ↗Git 📂](https://github.com/uutzinger/SerialUI) Terminal program to connect to MediBrick devices via USB and Bluetooth

### 🔌 **Firmware** 
Firmware created for MediBricks:
  - [↗Git 📂 AFE44XX](https://github.com/uutzinger/Arduino_AFE44XX) SPO2 Brick
  - [↗Git 📂 MAX3001G](https://github.com/uutzinger/Arduino_MAX30001G), ECG & BIOZ Brick
  - [↗Git 📂 DRV8704](https://github.com/uutzinger/Arduino_DRV8704), DC Controller

### 🧰 **Tools**
General libraries:
- [↗Git 📂 BLE Serial](https://github.com/uutzinger/Arduino_BLESerial), Serial communicaiton using Nordic UART for ESP
- [↗Git 📂 RingBuffer](https://github.com/uutzinger/Arduino_RingBuffer), Ringbuffer for microcontrollers
- [↗Git 📂 SG Filter](https://github.com/uutzinger/SavitzkyGolayFilter), Savitzky Golay Signal Filter

### 📋 **Test** 
Software to test individual components on a MediBrick

## Contributing
We welcome contributions! 

Please use [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) to create and change documentation.

## Contributors
<img src="Urs.png" alt="Pencil sketch portrait" width="50">

[Urs Utzinger](https://bme.engineering.arizona.edu/faculty-staff/faculty/urs-utzinger) 2026

Senior Capstone Teams:
- 2022/23: [23094](https://icap.engineering.arizona.edu/node/477)
- 2023/24: [24052](https://icap.engineering.arizona.edu/node/559)
- 2024/25: [26048](https://icap.engineering.arizona.edu/node/1387)
