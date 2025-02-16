# CP2102USB2UART

## 🚀 Overview
An open-source reverse-engineered version of the CJMCU CP2102 USB to UART TTL adapter, based on the original component available [here](https://fr.aliexpress.com/item/1005006975725106.html). This project aims to provide insights into USB-to-serial communication and offer a customizable alternative for embedded system developers.

## 🎯 Purpose
- 🔍 **Reverse engineering**: Understanding the design and functionality of the original adapter.
- 🛠️ **Skill development**: Enhancing expertise in PCB design and USB-to-serial communication.
- 🔄 **Future adaptation**: Leveraging this knowledge to develop custom USB-to-UART solutions for embedded systems.

## 📝 Features Comparison: Original vs. Reverse-Engineered

| Feature            | Original Adapter | Reverse-Engineered Version |
|--------------------|----------------|---------------------------|
| 🖥️ PCB Design        | Proprietary     | Open-source & customizable |
| 🔌 USB Connector     | Type-C & Micro USB | Type-C & Micro USB |
| 🏷️ Chipset           | CP2102          | CP2102 |
| 📌 Pin Mapping       | 6-Pin UART TTL  | 6-Pin UART TTL |
| ⚡ Supported Voltage | 3.3V / 5V       | 3.3V / 5V |
| 📐 Mechanical Drawing  | ![Original PCB Drawing](images/original_pcb.png) | ![Reverse-Engineered PCB Drawing](images/reversed_pcb.png) |
| 📷 Photo             | ![Original Circuit Photo](images/original_3d.png) | ![Reversed 3D View](images/reversed_3d.png) |

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

## 📜 License
This project is open-source. Feel free to use, modify, and contribute! 🚀

