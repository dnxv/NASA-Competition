# 1. Hardware

## 1.1 No Mods

|  Hexapod |  Under RPi  |
|---|---|
| ![](./1.%20Hex-Media/1.%20Hardware/1.%20no-mods-hex/before-hex-full.jpg) | ![](./1.%20Hex-Media/1.%20Hardware/1.%20no-mods-hex/Underneath%20Raspberry%20Pi/IMG_20221111_143821.jpg) | 

![](./1.%20Hex-Media/2.%20Software/5.%20Movement/coloredHex.gif)

## 1.2 Semi-mod

|  Front |  Top  |
|---|---|
| ![](./1.%20Hex-Media/1.%20Hardware/2.%20first-mods-parker/top-mods-hex-2.jpg) | ![](./1.%20Hex-Media/1.%20Hardware/2.%20first-mods-parker/top-mods-hex.jpg) |

![](./1.%20Hex-Media/3.%20Good%20to%20share/mid-mod-hex.png)

## 1.3 Final mods

|  Front |  Top  |
|---|---|
| ![](./1.%20Hex-Media/1.%20Hardware/3.%20final-mods-parker/Hexapod_20230324_25-corner-view.jpg) | ![](./1.%20Hex-Media/1.%20Hardware/3.%20final-mods-parker/Hexapod_20230324_25-top-view.jpg) |

 ![](./1.%20Hex-Media/2.%20Software/5.%20Movement/2.%20Incline/1.%20Final%20Rocky%20Incline/parker.gif)


# 2. Software
## 2.1 Avoidance

|  Side View  |  Top View  |
|---|---|
| ![](./1.%20Hex-Media/2.%20Software/1.%20Avoidance/FY7A0401-side-view.gif) | ![](./1.%20Hex-Media/2.%20Software/1.%20Avoidance/FY7A0399-top-view.gif) | 

| Lidar Distance Readings during Avoidance |
|---|
![](./1.%20Hex-Media/2.%20Software/1.%20Avoidance/Screenshot%202024-06-08%20004009.png)

## 2.2 Swarm

|  1st attempt  |  2nd attempt  |
|---|---|
| ![](./1.%20Hex-Media/2.%20Software/2.%20Swarm/swarm-1.gif) | ![](./1.%20Hex-Media/2.%20Software/2.%20Swarm/swarm02.gif) | 

![](./1.%20Hex-Media/2.%20Software/2.%20Swarm/swarm-terminal-messages.png)

## 2.3 Redundancy
### Imitating missing front leg

![](./1.%20Hex-Media/2.%20Software/3.%20Redundancy/GOPR0752-best.gif)
![](./1.%20Hex-Media/2.%20Software/3.%20Redundancy/leg1failure.gif)

| IMU Readings during Redundancy|
|---|
![](./1.%20Hex-Media/2.%20Software/3.%20Redundancy/run1.JPG)

## 2.4 Sensors

|  2.4.1 LiDAR  |  2.4.2 IR - Infrared  |
|---|---|
|  ![](./1.%20Hex-Media/2.%20Software/1.%20Avoidance/ultra4.JPG)  |  ![](./1.%20Hex-Media/2.%20Software/4.%20Sensors/IR%20-%20Infrared/RaspberryPi_IR.JPG) |
| LiDAR Diagram (Arduino) | IR Diagram (Rasp Pi) |
|  ![](./1.%20Hex-Media/2.%20Software/4.%20Sensors/Lidar/lidar-diagram.png)  | ![](./1.%20Hex-Media/2.%20Software/4.%20Sensors/IR%20-%20Infrared/IR_Diagram_Shared_with_Drone_Team.png) | |


|  2.4.3 Inertial Measuring Unit  |  2.4.4 Temp & Humidity  |
|---|---|
|  ![](./1.%20Hex-Media/2.%20Software/4.%20Sensors/IMU/stationaryimu.JPG)  | ![](./1.%20Hex-Media/2.%20Software/4.%20Sensors/Temperature/temperature.JPG) |


## 2.5 Movement

### 2.5.1 Incline

|  Side View of Hex on Slight Incline  | Under |
|---|---|
| ![](./1.%20Hex-Media/2.%20Software/5.%20Movement/2.%20Incline/2.%20Progress%20Incline/Hex_Incline_Rocks_1.gif) | ![](./1.%20Hex-Media/2.%20Software/5.%20Movement/2.%20Incline/2.%20Progress%20Incline/Hex_Incline_Rocks_2.gif) |


### 2.5.2 Sandbox
|  Single Leg  | Three Legs |
|---|---|
| ![](./1.%20Hex-Media/2.%20Software/5.%20Movement/1.%20Final-Sandbox/Hexapod_20230324_62.jpg) | ![](./1.%20Hex-Media/2.%20Software/5.%20Movement/1.%20Final-Sandbox/Hexapod_20230324_68.jpg) |

|  Full Hex  |
|---|
![](1.%20Hex-Media/hex-on-sand.jpg)

## 2.6 Computer Vision - Object Detection (Large Rocks)
|  TensorFlow Lite  |
|---|
![](1.%20Hex-Media/2.%20Software/6.%20Object%20Detection/11inches.jpg)
| ![](1.%20Hex-Media/2.%20Software/6.%20Object%20Detection/cv-rock.jpg) |

Original Hexapod Code: https://github.com/Freenove/Freenove_Big_Hexapod_Robot_Kit_for_Raspberry_Pi

Object Detection: https://github.com/tensorflow/examples/tree/master


---
# Folder Structure
```
NASA-Competition/
├── 1. Hex-Media/
│   ├── 1. Hardware/
│   │   ├── 1. no-mods-hex/
│   │   │   ├── before-hex-full.jpg
│   │   │   ├── before-hex-rpi-2.jpg
│   │   │   ├── before-hex-rpi.jpg
│   │   │   └── Underneath Raspberry Pi/
│   │   │       ├── IMG_20221111_143821.jpg
│   │   │       └── IMG_20221111_143824.jpg
│   │   ├── 2. first-mods-parker/
│   │   │   ├── top-mods-hex-2.jpg
│   │   │   └── top-mods-hex.jpg
│   │   ├── 3. final-mods-parker/
│   │   │   ├── Cables/
│   │   │   │   └── VID_20230317_105518.mp4
│   │   │   ├── Hexapod_20230324_25-corner-view.jpg
│   │   │   ├── Hexapod_20230324_25-top-view.jpg
│   │   │   ├── Hexapod_20230324_46.jpg
│   │   │   ├── Hexapod_20230324_47.jpg
│   │   │   └── Hexapod_20230324_52-birds-eye.jpg
│   │   └── Hexapod_Servo_Diagram.png
│   ├── 2. Software/
│   │   ├── 1. Avoidance/
│   │   │   ├── FY7A0399-top-view.gif
│   │   │   ├── FY7A0401-side-view.gif
│   │   │   ├── Screenshot 2024-06-08 004009.png
│   │   │   └── ultra4.JPG
│   │   ├── 2. Swarm/
│   │   │   ├── swarm-1.gif
│   │   │   ├── swarm-terminal-messages.png
│   │   │   └── swarm02.gif
│   │   ├── 3. Redundancy/
│   │   │   ├── GOPR0752-best.gif
│   │   │   ├── leg1failure.gif
│   │   │   └── run1.JPG
│   │   ├── 4. Sensors/
│   │   │   ├── IMU/
│   │   │   │   ├── Redundancy (5 legs) 1 step at a time.png
│   │   │   │   ├── Regular (6 legs) 1 step at a time.png
│   │   │   │   ├── stationary.csv
│   │   │   │   └── stationaryimu.JPG
│   │   │   ├── IR - Infrared/
│   │   │   │   ├── Calibration - Raspberry Pi (CPU).txt
│   │   │   │   ├── Calibration - Raspberry Pi (Whole Computer).txt
│   │   │   │   ├── Calibration - Table.txt
│   │   │   │   ├── IR_Diagram_Shared_with_Drone_Team.png
│   │   │   │   ├── RaspberryPi_IR.JPG
│   │   │   │   ├── RaspberryPiCPU_IR.JPG
│   │   │   │   ├── RaspberryPiCPU_IR2.JPG
│   │   │   │   ├── RaspberryPiCPU_IR3.JPG
│   │   │   │   └── TableTop_IR.JPG
│   │   │   ├── Lidar/
│   │   │   │   ├── lidar-diagram.png
│   │   │   │   ├── lidar_data_Test_1.csv
│   │   │   │   └── Lidar_Test_1.JPG
│   │   │   └── Temperature/
│   │   │       ├── temperature.JPG
│   │   │       └── temperature.txt
│   │   ├── 5. Movement/
│   │   │   ├── 1. Final-Sandbox/
│   │   │   │   ├── Hexapod_20230324_62.jpg
│   │   │   │   └── Hexapod_20230324_68.jpg
│   │   │   ├── 2. Incline/
│   │   │   │   ├── 1. Final Rocky Incline/
│   │   │   │   │   ├── gaitM3incline.png
│   │   │   │   │   └── parker.gif
│   │   │   │   └── 2. Progress Incline/
│   │   │   │       ├── Hex_Incline_Rocks_1.gif
│   │   │   │       └── Hex_Incline_Rocks_2.gif
│   │   │   └── coloredHex.gif
│   │   └── 6. Object Detection/
│   │       ├── 11inches.jpg
│   │       ├── 11inchesP3.jpg
│   │       └── cv-rock.jpg
│   ├── 3. Good to share/
│   │   └── mid-mod-hex.png
│   └── hex-on-sand.jpg
├── directory.py
└── README.md
```
