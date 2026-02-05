# Multi-Protocol Sensor Data Acquisition Using QCC744M

## Project Overview
This project demonstrates a multi-board embedded system using QCC744M development boards to collect environmental sensor data and transfer it across different communication protocols.

Sensor and time data are collected, transmitted between two boards, and finally sent to a PC for monitoring. The project mainly focuses on learning and implementing communication protocols in embedded systems.

---

## System Working
1. RTC module sends time data to Board-1 using I2C.
2. Board-1 collects sensor data from MQ135 and DHT11 sensors.
3. All collected data is transmitted from Board-1 to Board-2 via SPI.
4. Board-2 sends the received data to a PC using UART.
5. Data is displayed on the PC through a serial terminal.

---

## Hardware Components Used
- 2 × QCC744M Development Boards
- RTC Module
- MQ135 Gas Sensor
- DHT11 Temperature & Humidity Sensor
- USB-to-UART Interface
- PC for monitoring output
- Power supply and connection wires

---

## Communication Protocols Used
- **I2C** – Communication with RTC module
- **Analog Input / GPIO** – Sensor data acquisition
- **SPI** – Communication between two QCC744M boards
- **UART** – Communication between Board-2 and PC

---

## Project Objective
- Understand practical usage of embedded communication protocols
- Learn sensor interfacing techniques
- Implement multi-board communication
- Gain experience with QCC744M platform
- Develop a complete embedded data acquisition system

---

## Repository Structure

