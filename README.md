# Intelligent Factory Machine Monitoring

An Industrial Internet of Things (IIoT) based machine monitoring system designed to monitor the operating conditions of industrial machines and motors using embedded systems, sensors, and edge computing.

## Overview

The Intelligent Factory Machine Monitoring system aims to improve machine monitoring and operational visibility through real-time sensor data acquisition and visualization.

The prototype uses an ESP32-based sensor node to collect machine operating parameters and a Raspberry Pi as an edge computing platform. Sensor data is communicated using MQTT and can be visualized through a monitoring dashboard.

The system focuses on monitoring important machine parameters such as temperature, vibration, and rotational activity.

## Project Objectives

- Monitor machine operating conditions in real time.
- Measure motor temperature and vibration.
- Detect rotational activity using a Hall-effect sensor.
- Transfer sensor data using MQTT communication.
- Use Raspberry Pi for edge data processing.
- Visualize machine parameters through a monitoring dashboard.
- Explore the foundation for predictive maintenance.

## System Architecture

**Sensor Layer**
- ESP32 microcontroller
- DS18B20 temperature sensor
- MPU6050 accelerometer and gyroscope
- Hall-effect sensor (A3144)

**Edge Computing Layer**
- Raspberry Pi
- Sensor data processing
- MQTT communication

**Monitoring Layer**
- MQTT-based data transmission
- Monitoring dashboard
- Machine operating parameter visualization

## Hardware Components

| Component | Purpose |
|---|---|
| ESP32 | Main sensor node |
| Raspberry Pi | Edge computing |
| DS18B20 | Temperature monitoring |
| MPU6050 | Vibration and motion monitoring |
| A3144 Hall Sensor | Rotational activity detection |
| DC Geared Motor | Machine prototype |
| Buzzer | Alert indication |

## Software and Technologies

- Embedded C / C++
- Python
- ESP32 Development
- Raspberry Pi
- MQTT Protocol
- IoT Dashboard
- Sensor Integration
- Edge Computing

## Working Principle

1. Sensors collect machine operating parameters.
2. ESP32 reads and processes the sensor measurements.
3. Sensor data is transmitted through MQTT.
4. Raspberry Pi receives and processes the incoming data.
5. Machine parameters are presented through a monitoring dashboard.
6. Alert mechanisms can indicate abnormal operating conditions.

## Applications

- Industrial machine condition monitoring
- Motor health monitoring
- Smart manufacturing
- Industrial IoT applications
- Predictive maintenance research

## Project Status

**Development in Progress**

This project is being developed as an Industrial IoT prototype. Hardware integration, sensor data acquisition, MQTT communication, and dashboard development are part of the implementation.

## Future Improvements

- Machine anomaly detection
- Predictive maintenance algorithms
- Historical sensor data analysis
- Cloud-based monitoring
- Advanced alert and notification system
- Multi-machine monitoring

## Author

**Upendra Gupta**

Embedded Software Engineer | IoT and Smart Systems

## License

This project is licensed under the MIT License.
