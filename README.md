# Mini AI Camera Module

[![Mini AI Camera Module](https://raw.githubusercontent.com/BackLogers/Mini-AI-Camera-Module/refs/heads/main/images/module-image.jpg)](https://github.com/BackLogers/Mini-AI-Camera-Module/tree/main)

## Project Description

The **Mini AI Camera Module** is a compact platform based on the **ESP32-S3**, combining a standard visible-light camera with a **LiDAR** sensor. The module is designed as a low-cost solution for implementing simple AI algorithms, image recognition, and basic 3D depth perception.

This project includes:
- **OV5640** visible-light camera (5 MP)
- **VL53L5CX** LiDAR camera with an **8×8 pixel** depth map  

*(A future hardware revision is planned to include the **VL53L9CX** sensor featuring a 54×42 pixel resolution.)*

## Key Features

1. **Compact size: 25×25 mm**  
   The module includes mounting holes for easy installation, e.g., in mobile robots.

2. **Two complementary imaging systems**  
   - **OV5640 – 5 MP visible-light camera**  
   - **VL53L5CX – 8×8 pixel LiDAR sensor**

3. **Low production cost**  
   - Uses popular and cost-effective electronic components  
   - PCB designed with simple manufacturing requirements  
   - Complete **JLCPCB** production files included

4. **Ideal for autonomous and IoT projects**  
   Suitable for robotics, autonomous vehicles, perception systems, and IoT devices.

5. **Wireless connectivity**  
   With the ESP32-S3, the module supports:  
   - WiFi  
   - Bluetooth  
   - **ESP-NOW**

6. **Convenient USB and UART interfaces**  
   - Vertical **USB-C** port allows direct mounting to a robot chassis  
   - **SBU1 and SBU2** lines are exposed as **UART**, enabling easy integration with external devices

## Repository Contents

- Technical documentation  
- Schematics and PCB design  
- JLCPCB fabrication files  
- Example firmware for **Arduino**
