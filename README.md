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
*Insert image here showing hand landmarks detected by MediaPipe.*

### Robotic Arm Components
*Insert image here showing 3D-printed InMoov parts.*

### Full Assembly
*Insert image here showing the fully assembled robotic arm.*
