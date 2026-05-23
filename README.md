AUTONOMOUS & BLUETOOTH CONTROLLED RC CAR 

PROJECT OVERVIEW 

This project is a dual-mode autonomous RC car designed using a handmade chassis and controlled by an Arduino Uno. The car can operate in:
Bluetooth Manual Control Mode – controlled wirelessly through a mobile phone.
Autonomous Obstacle Avoidance Mode – detects obstacles using ultrasonic sensors and automatically selects a safe path.
The project combines robotics, embedded systems, motor control, wireless communication, and sensor-based automation into a single smart RC car platform.

KEY FEATURES 

📱 Bluetooth Mobile Control using smartphone app
🤖 Autonomous Navigation Mode
🚧 Obstacle Detection and Avoidance
🔄 Dual Operation Modes (Manual + Autonomous)
⚡ Real-time Motor Control
🛠 Custom Handmade Chassis Design
🎯 Path Decision Logic based on sensor input

HARDWARE COMPONENTS USED 

Arduino Uno - 1 - Main controller
DC BO Motors - 4 - Wheel movement
Wheels - 4 - Locomotion
HC-05 Bluetooth Module - 1 - Mobile wireless control
HC-SR04 Ultrasonic Sensor - 1 -Obstacle detection
L293D Motor Driver - 1 - Motor control
Battery / Power Supply - 1 - System power
Handmade Chassis - 1 - Car body structure
Jumper Wires - Multiple Connections 

WORKING PRINCIPLE 

1. Bluetooth Control Mode
The car connects to a smartphone through the Bluetooth module.
Mobile commands are sent wirelessly to the Arduino Uno.
Arduino processes the commands and controls the motors accordingly.
Functions:
Forward
Backward
Left
Right
Stop

2. Autonomous Mode
Ultrasonic sensor continuously measures distance from obstacles.
If an obstacle is detected:
Car stops
Scans for a free path
Chooses a safe direction
Continues moving automatically

SYSTEM ARCHITECTURE 

Mobile App → Bluetooth Module → Arduino Uno → Motor Driver → Motors
Ultrasonic Sensor → Arduino Uno → Decision Logic → Car Movement

Software Used

Arduino IDE
Embedded C / Arduino Programming
Bluetooth Control App

PROJECT HIGHLIGHTS 

Developed a smart dual-mode RC car with both manual and autonomous control.
Implemented wireless Bluetooth communication for mobile-based operation.
Integrated sensor-based obstacle detection for autonomous navigation.
Designed and built a custom handmade chassis.
Developed embedded control logic for real-time path decision making.

APPLICATIONS 

Robotics learning
Autonomous vehicle basics
Embedded systems projects
Obstacle avoidance systems
Wireless control systems
STEM educational demonstrations

FUTURE IMPROVEMENTS 

Add camera for FPV control
GPS-based navigation
Voice control
Line following mode
IoT remote monitoring
Better path planning algorithms
