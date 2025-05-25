# Smart Bed IoT Project – Cloud-Based Alexa Voice Control

This project analyzes and documents an IoT-based smart home solution that allows controlling an adjustable bed via Amazon Alexa, using AWS services such as Lambda, IoT Core, and MQTT.

## 📘 Context
Project completed by **Ahmad Hussein** as part of the *Cloud Computing* course supervised by **Dr. Marlène Seif**,  
Master 1 Data Science – Université Saint-Joseph de Beyrouth, 2023.

## 🛏️ Use Case
The bed is originally Bluetooth-controlled. This prototype enables:
- Voice commands via Alexa
- Serverless execution via AWS Lambda
- Real-time MQTT message delivery to the bed's BLE-enabled chip

## ⚙️ Architecture Overview
- **Input:** User speaks to Alexa
- **Processing:** Alexa Skill → AWS Lambda → AWS IoT
- **Output:** BLE command sent to adjustable bed

## 🔗 Key Technologies
- **Amazon Echo & Alexa Skills Kit**
- **AWS Lambda** (Serverless compute)
- **AWS IoT Core** (MQTT message broker)
- **Bluetooth LE (BLE)** command decoding
- **Raspberry Pi / CHIP SBC**

## 📶 BLE Command Examples
| Command | Hex Code |
|--------|-----------|
| Head & Foot Massage On | `e5fe160001000005` |
| Flat Preset | `e5fe1600000008fe` |
| Lift Head | `e5fe160100000005` |
| Lower Foot | `e5fe1608000000fe` |

## 🧠 Suggested Improvements
- Multi-device support in one environment (e.g., children's room or hospital)
- Bed-specific naming and contextual voice mapping

## 📁 Files
- `Projet_IoT_Cloud.pdf` – Full project report and diagrams

---

## 🏥 Wider Applications
- **Elderly care:** voice-controlled chairs in shared rooms
- **Neonatal care (NICU):** urgent voice-activated alerts

---

## 📜 License
MIT License (or other if required)


