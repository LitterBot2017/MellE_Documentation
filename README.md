# MellE Documentation
This repository documents the codebase and some of the hardware requirements for the CMU Litter-picking Robot Project a.k.a. Mell-E (Mobile Electro-Mechanical Litter Locator - Earth Class).

## Hardware Requirements
* Mobile-Base

## Software Requirements
There's a lot of software requirements so I've done my best to document them below

### Required Non-ROS Packages
* CUDA (for YOLO)
* OpenCV 3?

### Required "Local" ROS Packages
* [planning](https://github.com/LitterBot2017/planning)
* [yolo2](https://github.com/LitterBot2017/ROS_Yolo2)
* [object_tracker](https://github.com/LitterBot2017/object_track)
* [navigation](https://github.com/LitterBot2017/melle_refactored)

### Repos that I'm not sure are still dependencies, but wouldn't hurt to also include
* [arduino_pc](https://need_to_create_repo)
* [obstacle_avoidance](https://github.com/LitterBot2017/MellEObstacle)
* [state](https://need_to_create_repo)

### Required for Arduino
[MellE_Arduino_Refactored](https://github.com/LitterBot2017/MellE_Arduino_Refactored)

### Required General ROS Packages
To install `sudo apt-get install ros-indigo-{package-name}`
* ros-indigo-rosserial-*
* ros-indigo-joy

### CPR Mover4 Arm Software
[Documentation](https://github.com/CPR-Robots/cpr_mover/blob/master/doc/CPRMoverROSDoc.pdf)



### Repos for Our Custom Cloud Interface
* Android App - [MellEAndroid](https://github.com/LitterBot2017/MellEAndroid)
* Heroku Server Code - [MellEBackend](https://github.com/LitterBot2017/MellEBackend)
* ROS Client Node - [heartbeat](https://need_to_create_repo)
