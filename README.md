# Multi-Sensor Environmental Monitoring System using LPC2129

## 📌 Project Overview

An embedded systems project using the **LPC2129 ARM7 microcontroller** to monitor environmental parameters through multiple sensors. The system collects sensor readings, processes the data, and displays environmental conditions through a 16×2 LCD and UART terminal.

## ✨ Features

- Temperature monitoring using LM35 sensor.
- Light intensity monitoring using LDR.
- Soil moisture monitoring.
- Water detection.
- Environmental status indication using LEDs.
- LCD-based sensor data display.
- UART-based monitoring through PC terminal.

## 🛠️ Technologies Used

| Category | Components / Technologies |
|---|---|
| Microcontroller | LPC2129 (ARM7) |
| Programming Language | Embedded C |
| IDE | Keil µVision |
| Temperature Sensor | LM35 |
| Light Sensor | LDR |
| Soil Sensor | Soil Moisture Sensor |
| Water Sensor | Water Detection Sensor |
| Peripherals | ADC, GPIO, UART |
| Display | 16×2 LCD |
| Indicators | Green, Yellow and Red LEDs |

## ⚙️ Working Principle

1. Sensors collect environmental data such as temperature, light intensity, soil moisture, and water presence.
2. LPC2129 reads analog sensor values using ADC and digital sensor signals using GPIO.
3. The microcontroller processes the collected sensor data.
4. Sensor readings are compared with predefined threshold values.
5. Environmental conditions and system status are displayed on the LCD and UART terminal.
6. LEDs provide visual indications of the detected environmental conditions.

## 🔌 Hardware Components

- LPC2129 ARM7 Development Board
- LM35 Temperature Sensor
- LDR Sensor
- Soil Moisture Sensor
- Water Sensor
- 16×2 LCD Display
- Green LED
- Yellow LED
- Red LED
- Connecting Wires
- Power Supply

## 📊 Expected Output

```text
-----------------------------------------
Temperature    : 30.5 °C
Light Level    : NORMAL
Soil Moisture  : 72 %
Water Sensor   : NOT DETECTED
System Status  : SAFE
LED Status     : GREEN
-----------------------------------------
```

## 📂 Project Structure

```text
Multi-Sensor-Environmental-Monitoring-System/
│
├── main.c
├── delay.c
├── gpio.c
├── lcd.c
├── uart.c
├── adc.c
├── sensors.c
│
├── header.h
│
└── README.md
```

## 🌍 Applications

- Environmental monitoring systems.
- Smart agriculture.
- Greenhouse monitoring.
- Automated irrigation systems.
- Water leakage detection.
- Environmental condition monitoring.

## 👩‍💻 Developed By

**Ishwari Sampatakumar Bilagi**

- GitHub: https://github.com/ishwaribilagi-gif
- LinkedIn: https://www.linkedin.com/in/ishwari-bilagi-61b762277

## 📝 Project Status

Developed using Embedded C and LPC2129 ARM7 microcontroller as part of embedded systems learning and practical implementation.

---

⭐ If you find this project useful, feel free to explore the repository!
