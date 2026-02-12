# Drone-FLying 🛸

A modular flight control and interfacing system designed for DIY drones. This project provides a bridge between software controllers and drone hardware, allowing for manual control and autonomous system development using Python and Arduino.

## 🚀 Overview

This project is a cost-effective alternative to traditional transmitter/receiver setups. It uses a Python-based GUI to interact with the drone, allowing for sensor calibration, motor testing, and phased flight development.

## ✨ Features

* **Python Interface:** Built with Kivy for real-time command sending.
* **Stabilization:** Integrated MPU6050 (Gyroscope + Accelerometer) support.
* **Phased Testing:** Structured workflow from preparation to full air testing.
* **Cross-Platform:** Developed on Linux; compatible with Windows and macOS.

## 🛠️ Hardware Requirements

* **Microcontroller:** Arduino (Uno, Nano, or Mega)
* **Sensors:** * MPU6050 (IMU)
    * HC-SR04 (Ultrasonic)
* **Wireless:** HC-05 Bluetooth Module
* **Propulsion:** DC Motors/ESCs, Propellers, and LiPo Battery

## 💻 Software Setup

### 1. Prerequisites
Ensure you have Python 3.x installed. You will need the `Kivy` and `pyserial` libraries:

```bash
pip install kivy pyserial
