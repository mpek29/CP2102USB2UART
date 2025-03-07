# CP2102USB2UART

## 🚀 Overview
![Main Preview](assets/img/main.png)

An open-source reverse-engineered version of the CJMCU CP2102 USB to UART TTL adapter, based on the original component available [here](https://fr.aliexpress.com/item/1005006975725106.html). This project aims to provide insights into USB-to-serial communication and offer a customizable alternative for embedded system developers.

## 🎯 Purpose
- 🔍 **Reverse engineering**: Understanding the design and functionality of the CP2102USB2UART.
- 🛠️ **Skill development**: Enhancing expertise in PCB design and USB-to-serial communication.
- 🔄 **Future adaptation**: Leveraging this knowledge to develop custom USB-to-UART solutions for embedded systems.

## 📝 Features Comparison: Original vs. Reverse-Engineered

| Feature            | Original Module | Reverse-Engineered Version |
|--------------------|----------------|---------------------------|
| 🖥️ PCB Design        | Proprietary     | Open-source & customizable |
| 🔌 USB Connector     | Micro USB | Micro USB |
| 🏷️ Chipset           | CP2102          | CP2102 |
| 📌 Pin Mapping       | 6-Pin UART TTL  | 6-Pin UART TTL |
| ⚡ Supported Voltage | 3.3V / 5V       | 3.3V / 5V |
| 👐 Mechanical Drawing  | <img src="assets/img/original_pcb.png"> | <img src="assets/img/reversed_pcb.png"> |
| 📝 Reverse-Engineered Schematic | N/A | <img src="assets/img/reversed_sch.png"> |
| 📷 Photo             | <img src="assets/img/original_3d.png"> | <img src="assets/img/reversed_3d.png"> |

## 🛠️ How to Use
### 📌 Wiring Guide
| CP2102 Pin | Description |
|------------|-------------|
| TXD        | Transmit Data |
| RXD        | Receive Data |
| GND        | Ground |
| 3V3        | 3.3V Power Output |
| 5V         | 5V Power Output |
| DTR        | Data Terminal Ready |

## 🌟 License
This project is open-source. Feel free to use, modify, and contribute! 🚀


