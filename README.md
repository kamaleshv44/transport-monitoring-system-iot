# IoT Transport and Monitoring of Goods with Wireless Sensors

Final year ECE project (2024-2025) for real-time monitoring of sensitive goods (e.g., medicines, vaccines, organs) using IoT sensors to track temperature, humidity, vibration, and location.

## Overview
- **Problem**: Traditional monitoring is manual and error-prone; deviations can compromise goods.
- **Solution**: IoT network with wireless sensors, MQTT for secure messaging, CRC-32 error detection, and elliptic curve keys for encryption.
- **Key Features**: Real-time data transmission, remote access, accuracy 89.88%, F1-score 0.686.
- **Team**: Solo/Individual (based on your doc).

## Technologies Used
- Hardware: Arduino, Temperature/Humidity Sensors, Mini Cooling Box.
- Software: MQTT Protocol, Secure Short Message Service.
- Literature Survey: 
  - [1] IoT-Enhanced Medicine Transport (Bhatti et al., 2024): Mobile ops, Arduino, CRC-32.
  - [2] ML-Based Water Leakage Detection (Rezwanal et al., 2023): Edge ML, Piezo microphone, 98.96% accuracy.
  - [3] Real-time Temp Control (Han & Yang, 2022): Wireless sensor networks for env monitoring.

## Implementation
- **Block Diagram**: ![Intro Diagram](images/intro-diagram.png) (from your PDF Ch.1).
- **Code**: Arduino sketch for sensor data collection and MQTT publishing (e.g., `sensor_monitor.ino`).
- **Setup**: Deploy sensors on vehicles; encrypt/transmit data to stakeholders.

## Results & Challenges
- Benefits: Enhanced reliability, safety, efficiency.
- Challenges: Implementing across sectors; data integrity.
- Full Report: [final-year-project.pdf](docs/final-year-project.pdf)

## Skills Demonstrated
- IoT Networking, Sensor Integration, Data Encryption, Real-time Systems.

## How to Run
1. Clone repo: `git clone https://github.com/kamaleshv44/iot-goods-monitoring.git`
2. Install dependencies (e.g., Arduino IDE, MQTT libs).
3. Upload `sensor_monitor.ino` to Arduino.

License: MIT
