# Gesture-Controlled Robotic Arm Using OpenCV and Arduino

This project demonstrates a gesture-controlled robotic arm capable of responding to hand movements in real-time. By integrating computer vision with robotic components, the arm can interpret gestures through a camera feed, enabling hands-free control over its movements.

## Project Overview

Using OpenCV and the MediaPipe library, this project detects and maps hand gestures, which are then translated into commands for the robotic arm. The arm is constructed from 3D-printed InMoov parts and is powered by 996R servo motors controlled by an Arduino Uno. Hand landmarks are plotted through computer vision, allowing precise gesture-based control of the arm's motion.

## Technologies and Components

- **Python** for image processing and hand tracking
- **OpenCV** and **MediaPipe** to identify hand gestures and landmarks
- **Arduino Uno** as the microcontroller for servo control
- **996R Servo Motors** to enable movement of arm parts
- **3D Printed InMoov Parts** for the arm structure

## Features

- **Gesture Recognition**: Uses OpenCV and MediaPipe to detect hand movements in real-time, tracking key points on the hand for gesture interpretation.
- **Servo Control**: Maps detected gestures to specific servo motor movements, allowing intuitive control over the robotic arm’s functions.
- **3D Printed Design**: Utilizes customizable InMoov parts for the robotic arm, providing a scalable and flexible design.

## Project Images

### Hand Tracking with MediaPipe
![image](https://github.com/user-attachments/assets/0caa4462-1b36-411f-999c-3f5b54c796d7)

### Robotic Arm Components
![image](https://github.com/user-attachments/assets/76247be3-28fe-4515-bc8d-555bb22693d1)

### Full Assembly
![robotArm](https://github.com/user-attachments/assets/467d72d7-fc7c-4ce2-af33-bac3fae8bfd6)

