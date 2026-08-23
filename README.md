# VehicleAssist-ADAS 🚗

A vision-based **Advanced Driver Assistance System (ADAS)** built using **Raspberry Pi 4 (2 GB)** and a camera.

## Features

* **FCWS** – Forward Collision Warning System
* **LDWS** – Lane Departure Warning System
* **LKAS** – Lane Keeping Assistance System

## Technologies

* Raspberry Pi 4 (2 GB)
* Python
* OpenCV
* YOLOv9 / EfficientDet – Object Detection
* Ultra-Fast-Lane-Detection – Lane Detection

## System Overview

```text
Camera
   ↓
Raspberry Pi 4
   ↓
Object Detection + Lane Detection
   ↓
ADAS Decision System
   ↓
FCWS / LDWS / LKAS
```

## Development

The project will initially develop and test each detection module separately before integrating them into a complete vision-based ADAS system.

> **Note:** This project is intended for educational and research purposes.
