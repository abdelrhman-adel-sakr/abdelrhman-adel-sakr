<div align="center">

# Hey, I'm Abdel-Rhman 👋
### Electronics & Communication Engineering Student @ MIU Cairo
#### Designing cloud architectures and embedded systems that talk to the real world.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdelrhman-sakr-6a80552b6)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdelrhmansakr248@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdelrhman-adel-sakr)

</div>

---

## 🧑‍💻 About Me

I'm a final-year ECE student passionate about **cloud architecture** and **embedded software engineering**. I love designing scalable, serverless cloud systems — and I'm equally at home writing firmware that runs close to the metal.

- 🎓 B.Sc. Electronics & Communication Engineering — **Misr International University** (2021–2026) | GPA: 3.21/4.0
- 📍 El Obour, Cairo, Egypt
- ☁️ Aspiring **Cloud Architecture Engineer** — designing serverless, event-driven systems on AWS
- 🔌 Also passionate about **Embedded Software Engineering** — firmware, RTOS, and IoT
- 🌉 Uniquely positioned at the intersection: cloud infrastructure that talks directly to hardware


---

## 🚀 Featured Projects

### 💡 [Smart Campus Lighting System](https://github.com/abdelrhman-adel-sakr/smart-campus-lighting)
> Serverless, event-driven cloud architecture controlling physical hardware in real time

- Designed a fully serverless AWS architecture: EventBridge → Lambda → DynamoDB → IoT Core
- Lambda (Python 3.12) evaluates lecture schedules every minute and publishes MQTT control bit-masks to AWS IoT Core
- Two DynamoDB tables with composite keys: permanent schedule store + TTL-enabled temporary session table
- REST API (API Gateway + Lambda) for creating auto-expiring temporary sessions via DynamoDB TTL
- ESP8266 firmware subscribes to IoT Core topics and drives a 74HC595 shift-register chain via SPI to control 16 independent room lights

`AWS Lambda` `DynamoDB` `IoT Core` `EventBridge` `API Gateway` `ESP8266` `MQTT/TLS` `Python`

---

### 🏠 Smart Home Automation System
> Real-time sensor-driven control on an AVR microcontroller

- PWM fan speed and lighting intensity control based on live ADC sensor readings
- Interrupt-driven sensor polling for responsive control without blocking the main loop

`Embedded C` `AVR` `ADC` `PWM` `Proteus`

---

### 🔐 Door Locker Security System
> Dual-MCU embedded security system with persistent password storage

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
| ☁️ **Cloud Architecture** | AWS (Lambda, DynamoDB, IoT Core, EventBridge, API Gateway, S3, IAM, CloudWatch), Serverless Architecture, Event-Driven Design, MQTT/TLS, REST APIs |
| 🔌 **Embedded Software** | AVR, ESP8266, ARM Cortex-M, AUTOSAR, Embedded C, FreeRTOS (basics) |
| 💻 **Programming** | C, C++, Python, MATLAB |
| 🌐 **Networking** | CCNA Fundamentals — IP Addressing, Routing, Switching, Subnetting, TCP/IP |
| 🧰 **Tools** | Git, VS Code, Eclipse, Code Composer Studio |
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

*"I design cloud systems that scale — and firmware that runs when the cloud can't reach."*

</div>
