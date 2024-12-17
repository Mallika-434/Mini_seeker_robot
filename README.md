
# Face Recognition and Robotic Control System

## Description
This repository contains a series of Python scripts and a literature survey related to face recognition technologies and robotic control systems. The face recognition system is designed to encode, recognize, and manage face data, while the robotic control system leverages IoT technology and ESP32-CAM for navigational control in various applications.

## Projects

### Face Recognition System
- `encode_face_recognition.py`: Encodes face data using either `cnn` or `hog` methods to create a serialized database of facial encodings.
- `face_recognition.py`: Implements face recognition to identify and interact with faces in real-time through a Raspberry Pi camera stream.
- `face_save.py`: Captures and saves face data by detecting faces and storing the images in a specified directory.

### Robotic Control System
- `robo_controls.py`: Controls a mini-sized search robot that navigates through confined spaces, equipped with camera and IoT capabilities for real-time data streaming and remote control.

## Literature Survey
- `Final Project- Literature Survey.docx`: Discusses the integration of ESP32-CAM with IoT in robotic systems, focusing on the scope of smart search robots, image recognition technologies, and the challenges faced in the implementation of these technologies.

## Usage
To use the face recognition scripts, ensure that you have the required libraries installed and a Raspberry Pi set up with a camera. For robotic control, an ESP32-CAM and appropriate GPIO setup on your Raspberry Pi are necessary.

### Setting up the Face Recognition System
1. Ensure you have Python 3.x, OpenCV, and the `face_recognition` library installed.
2. Run the scripts as per the instructions in the comments to encode and recognize faces.

### Operating the Robotic Control System
1. Setup your Raspberry Pi with the required GPIO connections as outlined in `robo_controls.py`.
2. Execute the script to start controlling your robot via the specified web interface or autonomously based on sensor data.

## Requirements
- Raspberry Pi 3/4
- Python 3.x
- OpenCV
- ESP32-CAM
- Internet connection for IoT capabilities
- Various libraries listed in each script

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

