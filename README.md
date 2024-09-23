# ras_main_micro_driver
C++ driver software for vessel microprocessors that handle actuation

This project is in construction (sept 2024 - BB)

The goal of this project is to make a generalized microcontroller driver (c++ based) that can be rolled out on various boards (e.g. Picos, Arduinos, ESP32s) to facilitate control of an arbitrary amount of dcmotors+encoder and Servo combinations. This stack could potentially be a single software to maintain for various vessel/project lines. 

This often comes in combination with a ROS_microcontroller bridge, although thats a different project. This is the software on the microcontroller. 
