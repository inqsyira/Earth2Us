# 🌱 Earth2Us — 5G IoT Smart Plug Prototype

**12th place — ZTE NextGen 5G Hackathon 2024 (Solo Project)**
*A one-month build using Raspberry Pi + AWS to explore 5G-enabled green energy solutions.*

## 📌 About This Project

Earth2Us is my first ever hackathon project — a **5G-enabled IoT smart plug prototype** designed to help consumers monitor and optimize their home energy usage in real time.

This project was built **solo in one month**, where I:

* self-learned IoT fundamentals
* researched and proposed the solution
* built the hardware prototype (sensors, relay, Raspberry Pi)
* designed the full AWS serverless cloud backend
* integrated 5G connectivity using the SIM8200EA-M2 module

Despite being a beginner in IoT, this project earned **12th place (Top 20)** in the **ZTE NextGen 5G Hackathon 2024**.

## 🎯 Hackathon Theme

**Empowering Efficiency, Safety, and Mobility through 5G-enabled solutions**
The hackathon focuses on leveraging 5G technology to address real-world challenges aligned with the UN Sustainable Development Goals (SDGs), especially:

* **SDG 9:** Industry, Innovation & Infrastructure
* **SDG 11:** Sustainable Cities & Communities

Categories included:

* Infrastructure
* Healthcare
* Smart Cities
* Environment

Earth2Us falls under **Environment**, promoting greener habits through smart energy usage.

## ⚡ Project Idea: Earth2Us Smart Plug

A smart plug that:

* monitors real-time energy usage
* predicts consumption trends
* encourages greener behavior
* helps reduce electricity bills
* connects to a 5G network for fast, stable data streaming

## 🧩 Hardware Stack

* **Raspberry Pi** (self-provided)
* **SIM8200EA-M2 5G Hat** (provided by ZTE/MMU)
* Relay module
* Current/voltage sensor
* Antennas & 5G enclosure

## 🛠️ Software & Cloud Stack

* **AWS IoT Core**
* **AWS Lambda**
* **AWS DynamoDB**
* **AWS S3**
* **AWS Greengrass** (for local IoT edge compute)
* Python for device-side scripts
* REST endpoints for data processing

## 📡 Why 5G?

Earth2Us leverages 5G for:

* low-latency telemetry transmission
* stable connection for real-time energy data
* scalability for future multi-device environments

## 🏗️ System Architecture (Simple Overview)

1. Raspberry Pi reads energy data from sensors
2. Data is sent via 5G (SIM8200EA-M2 + 5G Hat)
3. AWS IoT Core receives the data
4. Lambda functions process and store it
5. DynamoDB keeps live usage logs
6. S3 stores historical data for analysis
7. Dashboard (future work) visualizes energy usage

## 🌿 Impact & Potential

Earth2Us supports greener living by:

* giving users real-time visibility into their energy footprint
* enabling smart energy habits
* reducing electricity waste
* encouraging households to adopt sustainable IoT solutions



