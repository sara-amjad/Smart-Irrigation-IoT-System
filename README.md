# 🌱 Smart IoT-Based Irrigation System (Mehrano Agri Farms)
**Author:** Sara Amjad | **Date:** May 2026  

> **Academic Context:**  
This project was developed as part of Unit 20: Internet of Things under the Pearson BTEC HND in Digital Technologies. The system demonstrates the design and implementation of an IoT-based smart irrigation solution for a simulated agricultural environment, focusing on real-time monitoring, cloud integration, automation, and data-driven decision-making.


## 📌 Project Overview
This repository presents an IoT-enabled smart irrigation system designed for a simulated version of Mehrano Agri Farms Ltd. The system integrates sensor-based environmental monitoring with cloud computing and automation technologies to improve irrigation efficiency and agricultural decision-making.

The solution collects environmental data such as soil moisture, temperature, humidity, pH, salinity, and rainfall using IoT sensor nodes. The data is transmitted through MQTT and REST APIs via a gateway to cloud platforms for processing and visualization.

The system uses Node-RED for rule-based automation, enabling automatic irrigation control based on predefined threshold conditions. Power BI dashboards are integrated to provide real-time visualization of environmental trends and system performance. Cisco Packet Tracer is used to simulate network communication and IoT device interaction within the system architecture.


## 🧠 Key Features

- 🌡 Real-time environmental monitoring using IoT sensors  
- 🌐 MQTT and REST API-based communication  
- ☁ ThingSpeak cloud integration for data storage and analysis  
- ⚙ Node-RED automation for irrigation control logic  
- 📊 Power BI dashboards for data visualization  
- 🔁 Cisco Packet Tracer network simulation  
- 🚰 Threshold-based automated irrigation system  
- 🏗 Edge-to-cloud IoT architecture implementation  


## 🏗 System Architecture
The system follows a **three-layer IoT architecture**:

- Device Layer: Sensors and MCU-based nodes  
- Network Layer: MQTT communication and DLG100 gateway  
- Application Layer: ThingSpeak, Node-RED, Power BI  


## 🔄 System Workflow

1. 🌱 Sensors collect environmental data  
2. 📡 Data transmitted via MCU and gateway  
3. ☁ Cloud storage using ThingSpeak  
4. ⚙ Node-RED processes irrigation rules  
5. 🚰 Automated irrigation control triggered  
6. 📊 Power BI visualizes system performance  

