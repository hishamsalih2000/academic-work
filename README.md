# Academic Work of Hisham Salih Hassan Salih

This repository serves as a portfolio of my academic research and significant project work. The papers here reflect my focus on the intersection of engineering, data analysis, and sustainable systems.

---

## Bachelor's Thesis

### Techno-Economic Feasibility of Solar-Powered Irrigation Systems: A Case Study in River Nile State, Sudan

*   **Institution:** University of Khartoum, Faculty of Engineering
*   **Degree:** Bachelor of Science in Mechanical Engineering (First Class Honours)
*   **[View Full Thesis PDF](BSc_Thesis_Solar_Energy_Feasibility_Study.pdf)**

#### Abstract

> This study evaluates the technical and economic feasibility of replacing diesel-powered irrigation systems with solar-powered alternatives for smallholder wheat farming in Abu Hamed, River Nile State, Sudan. In response to high fuel costs, unreliable diesel supply chains, and environmental pressures, solar energy offers a promising solution for off-grid agricultural irrigation in arid regions. The research combines agro-climatic and energy modeling tools. The Food and Agriculture Organization's CROPWAT model is used to determine crop water requirements based on local climatic data, while HOMER Pro is employed to simulate and compare diesel and solar-powered pumping systems. Key indicators such as seasonal irrigation demand, load profiles, energy costs, and emissions are assessed to support system design and decision-making. The analysis is based on a 10-hectare wheat farm, with a solar system sized at approximately 6.4 kW to meet irrigation needs. Results show that the solar-powered system reduces operating costs by around 60% and eliminates more than 3.5 tons of CO2 emissions per season.

---

## Master's Project: End-to-End IoT Environmental Monitoring Pipeline

*    **Institution:** Hochschule Offenburg (Winter Semester 2025/2026)
*    **Degree:** M. Sc. Renewable Energy and Data Engineering
*    **[View Full Project Report PDF](./IoT_Pipeline_Project_Report.pdf)**

**Objective:** Designed and deployed a decoupled, real-time IoT pipeline using edge processing, MQTT telemetry, and time-series data visualization.

**🚀 Tech Stack:**
* **Hardware:** ESP32-WROOM-32E, BME280 (I2C), LDR (Analog)
* **Embedded & IoT:** C++ (Arduino), Mosquitto MQTT, Node-RED
* **Data Storage & Viz:** InfluxDB v2, Grafana, Flux Query Language

**Key Engineering Highlights:**
* **Edge Processing:** Implemented software oversampling and a custom log-log regression model directly in C++ to linearize an analog LDR power-law response.
* **Decoupled Telemetry:** Utilized asynchronous MQTT (Publish/Subscribe) for non-blocking, high-frequency data transmission.
* **Data Pipeline:** Engineered a Node-RED middleware layer to serialize JSON payloads into strict InfluxDB Line Protocol.
* **Visualization:** Configured Grafana dashboards with Flux aggregate-window downsampling and deployed logic-based threshold alerting for anomaly detection.
