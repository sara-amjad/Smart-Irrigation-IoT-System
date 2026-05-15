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

## 🔄 3.1 System Implementation (Initial Deployment)
The initial phase focused on establishing the IoT smart irrigation system in a simulated environment for Mehrano Agri Farms Ltd.
- IoT System Configuration: Cisco Packet Tracer was used to set up an IoT environment that incorporated 
environmental sensors such as soil moisture, temperature, humidity, and other 
parameters with the MCU-PT microcontroller. The DLG100 gateway became linked 
with aggregating sensor data and MQTT service (SBC-PT) was set up to allow real 
time communication between devices and the gateway.
<p align="center">
  <img src="Images/IoT system setup.png" width="800"/>
</p>

- Cloud Channel and API Configuration: The ThingSpeak was setup as a cloud channel and had several data fields which 
included soil moisture, temperature, humidity, pH, salinity, light intensity, rainfall and 
pump status. Read and write API keys were generated which will aid in securing 
communication between the system and the cloud platform. 

<p align="center">
  <img src="Images/ThingSpeak API key configuration.png" width="600"/>
</p>
<p align="center">
  <img src="Images/ThingSpeak channel setup .png" width="600"/>
</p>

- Real-Time Data Monitoring: The IoT system allowed ensuring that the information would always be available in the 
established channel. The integration of the clouds and real-time data was successful 
and verified with the help of the graphical visualisations of the soil moisture and 
temperature.
<p align="center">
  <img src="Images/ThingSpeak graphs .png" width="800"/>
</p>

- Data Processing and Control Logic: Node-RED was used as a data processing and control logic. Sensors data have been 
collected and presented in payloads and farm logic has been executed to operate 
irrigation conditions. Dashboard elements such as gauges and trends were used to 
monitor system parameters.
<p align="center">
  <img src="Images/Node-RED flow .png" width="800"/>
</p>
<p align="center">
  <img src="Images/Node-RED dashboard.png" width="800"/>
</p>

- Dashboard Development: A monitoring dashboard was developed using Power BI to visualise environment 
parameters and system performance. The dashboard illustrates the trends in soil 
moisture, temperature and humidity, that can be used to analyse the state of the irrigation 
and overall system.

<p align="center">
  <img src="Images/Power BI dashboard(0).png" width="800"/>
</p>

## 🧪Testing and Feedback

The system was evaluated to verify functionality, data flow, and integration across all components.

- 🔍 Verified sensor-to-cloud data transmission via Node-RED and ThingSpeak  
- ⚙ Tested MQTT communication stability between devices and gateway  
- 📊 Evaluated Power BI dashboard responsiveness and data accuracy

<h3> Key feedback identified: </h3>

- Raw sensor data required cleaning for consistency  
- Dashboard visuals lacked clarity and structure  
- Limited real-time optimisation in monitoring outputs  

These observations guided system refinement in subsequent iterations.
## 🛠️Iterative Development and Enhancements
The system was improved through three structured iterations based on testing results.

### 🔁 Iteration 1: Data Refinement and Chart Improvement 

- Data cleaning logic in Node-RED was applied on sensor data preprocess before it could 
be sent.

<p align="center">
  <img src="Images/Node-RED flow showing data cleaning before ThingSpeak upload .png" width="700"/>
</p>

- ThingSpeak visualisations were simplified by adjusting the settings in the gauge chart 
and control to show environmental readings that could be more easily understood.
<p align="center">
  <img src="Images/ThingSpeak charts.png" width="700"/>
</p>

- Power BI dashboard was updated with a clean and formatted environmental data 
visualised with augmented visualisations, including trends and system status.
<p align="center">
  <img src="Images/Power BI dashboard(1).png" width="700"/>
</p>

### ⚙ Iteration 2: Enhanced Visualisation and Analytical Improvement 

- The Node-RED flow was adjusted adding to the dashboard logic and further data 
cleaning and other monitoring capabilities to improve real-time visualisation and 
readability of the system.
<p align="center">
  <img src="Images/Updated Node-RED flow.png" width="700"/>
</p>

- The Node-RED dashboard was modified to display monitoring outputs easier, more 
visually appealing formats and system status displays.

<p align="center">
  <img src="Images/Updated Node-RED dashboard.png" width="800"/>
</p>

- ThingSpeak visualisations were enhanced with MATLAB analytics to show the trend 
of the various variables and their relationship with the soil moisture to the temperature, 
the light intensity to rainfall and pH of the soil to the salinity.

<p align="center">
  <img src="Images/ThingSpeak MATLAB visualisations .png" width="800"/>
</p>

- Power BI dashboard was enhanced with multi-variable analysis in the shape of a 
combination chart, distribution of pump status, and other parameters, and optimized thevisuals with various types of charts.

<p align="center">
  <img src="Images/Power BI dashboard(2).png" width="800"/>
</p>

### 🎯 Iteration 3:  Final Dashboard Refinement and Real-Time Monitoring Enhancement 

- The Power BI dashboard was altered to coherent theme and standard layout with 
rounded containers to make visual layout more organised and professional.

- Interactive slicers were added to date range and pump status to allow users to easily 
filter environmental data and analyse system behaviour in a more efficient manner.

<p align="center">
  <img src="Images/Final Power BI dashboard.png" width="800"/>
</p>
<p align="center">
  <img src="Images/Power BI auto-refresh setup .png" width="600"/>
</p>
