 Smart Driver Safety System using Raspberry Pi and OpenCV

Project Overview

The Smart Driver Safety System is an AI-based embedded system designed to reduce road accidents by monitoring the driver's condition in real time. The system detects driver drowsiness, alcohol consumption, and vehicle accidents, and automatically sends emergency alerts using GSM communication.

This project combines Embedded Systems, Computer Vision, IoT, and Artificial Intelligence.



 Features

- Driver Drowsiness Detection using OpenCV and YOLO
- Alcohol Detection using MQ-3 Sensor
- Accident Detection using MPU6050 Accelerometer
- GSM-based Emergency SMS Alert
- Buzzer Warning System
- Motor Control using Relay
- Automatic Window Control using Servo Motor
-  Real-time Monitoring using Raspberry Pi



Hardware Used

- Raspberry Pi
- USB Camera
- MQ-3 Alcohol Sensor
- MPU6050
- GSM Module
- Servo Motor
- Relay Module
- Buzzer
- Power Supply


Software Used

- Python
- OpenCV
- YOLO
- Arduino IDE
- Raspberry Pi OS

Working Principle

1. Camera continuously monitors the driver's face.
2. OpenCV + YOLO detects eye closure and drowsiness.
3. MQ-3 detects alcohol concentration.
4. MPU6050 detects sudden impact or accidents.
5. Raspberry Pi processes all sensor data.
6. If danger is detected:
   - Buzzer turns ON
   - Relay stops the vehicle
   - Servo opens the window (if needed)
   - GSM sends an emergency SMS

 Project Structure

Smart-Driver-Safety-System
│── README.md
│── Documentation
│── Source_Code
│── Circuit_Diagram
│── Images
│── Results


Future Improvements

- GPS Live Tracking
- Cloud Monitoring
- Mobile App Integration
- AI-based Driver Emotion Detection
- Voice Assistant Support


Author

Saiprasad Mudimukkala 

B.Tech - Electronics and Communication Engineering

Embedded Systems Enthusiast
