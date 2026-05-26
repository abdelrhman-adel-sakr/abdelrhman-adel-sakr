<div align="center">

# Hey, I'm Abdel-Rhman 👋
### Electronics & Communication Engineering Student @ MIU Cairo
#### Building things that live in the cloud, run on hardware, and talk to each other.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdelrhman-sakr-6a80552b6)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdelrhmansakr248@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdelrhman-adel-sakr)

</div>

---

## 🧑‍💻 About Me

I'm a final-year ECE student who enjoys building systems end-to-end — from bare-metal firmware on a microcontroller all the way up to serverless cloud infrastructure and mobile apps. I don't just study concepts, I build real things with them.

- 🎓 B.Sc. Electronics & Communication Engineering — **Misr International University** (2021–2026) | GPA: 3.21/4.0
- 📍 El Obour, Cairo, Egypt
- ☁️ Deep interest in **serverless IoT architectures** and **cloud-connected embedded systems**
- 🔧 Comfortable at every layer: firmware → cloud → mobile

---

## 🚀 Featured Projects

### 💡 [Smart Campus Lighting System](https://github.com/abdelrhman-adel-sakr/smart-campus-lighting)
> Serverless, schedule-driven lighting automation for a university campus

- EventBridge triggers a Lambda every minute to evaluate lecture schedules and publish MQTT bit-masks to AWS IoT Core
- Two DynamoDB tables: permanent schedule store + TTL-enabled temporary session table
- ESP8266 firmware drives a daisy-chained 74HC595 shift-register chain via SPI to control 16 independent room lights
- Flutter mobile app creates ad-hoc lighting sessions via API Gateway + Lambda

`AWS Lambda` `DynamoDB` `IoT Core` `EventBridge` `API Gateway` `ESP8266` `Flutter` `MQTT/TLS` `Python`

---

### 🏠 Smart Home Automation System
> Real-time sensor-driven control on an AVR microcontroller

- PWM fan speed and lighting intensity control based on live ADC sensor readings
- Interrupt-driven sensor polling for responsive control without blocking the main loop

`Embedded C` `AVR` `ADC` `PWM` `Proteus`

---

### 🔐 Door Locker Security System
> Dual-MCU security system with persistent password storage

- Password-protected door locking with EEPROM persistence across power cycles
- UART + I²C inter-processor communication between a keypad HMI MCU and a motor/alarm control MCU

`Embedded C` `AVR` `UART` `I²C` `EEPROM`

---

### 🤖 Maze Solving Robot (Logic Simulation)
> Wall-following algorithm implemented entirely in hardware logic gates

- Built with 74-series combinational/sequential ICs, validated in Multisim before PCB layout

`Digital Logic` `74-series ICs` `Multisim`

---

## 🛠️ Technical Skills

| Domain | Skills |
|---|---|
| ☁️ **Cloud & DevOps** | AWS (Lambda, DynamoDB, IoT Core, EventBridge, API Gateway, S3, IAM, CloudWatch), Serverless Architecture, MQTT/TLS, REST APIs |
| 🔌 **Embedded Systems** | AVR, ESP8266, ARM Cortex-M, AUTOSAR, Embedded C |
| 💻 **Programming** | C, C++, Python, MATLAB, Dart (Flutter) |
| 🌐 **Networking** | CCNA Fundamentals — IP Addressing, Routing, Switching, Subnetting, TCP/IP |
| 🧰 **Tools & Frameworks** | Flutter, FreeRTOS, Git, VS Code, Eclipse, Code Composer Studio |
| 🔬 **Hardware & Simulation** | Proteus, Multisim, Oscilloscope |
| 🐧 **Operating Systems** | Linux Administration, Windows |

---

## 📜 Certifications

| Year | Certificate | Issuer |
|---|---|---|
| 2026 | AWS AI Practitioner (AIF-C01) | Udemy / Stephane Maarek |
| 2025 | AWS Cloud Practitioner (CLF-C02) | Udemy / Stephane Maarek |
| 2025 | Industrial Training Certificate | Systel Telecom |
| 2025 | Linux Administration | Edges for Training |
| 2024 | AUTOSAR Software Design | Edges for Training |
| 2024 | ARM Architecture | Edges for Training |
| 2024 | Standard Embedded Systems Diploma | Edges for Training |

---

<div align="center">

*"I build systems that span silicon and cloud."*

</div>
