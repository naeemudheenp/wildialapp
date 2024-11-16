# Wildlife Detection System using Arduino Uno and YOLO Algorithm

## Project Overview

This project aims to develop a wildlife detection system using an **Arduino Uno** integrated with the **WildialApp**. The system employs the **YOLO** algorithm for real-time wildlife detection through a camera module. Once wildlife is detected, the system triggers a warning to alert nearby individuals, helping in the protection and conservation of wildlife.

## Key Features

- **Wildlife Detection**: Uses YOLO algorithm for accurate real-time detection of wildlife.
- **Camera Integration**: Utilizes a camera module to capture images/videos for processing.
- **Arduino Uno**: Acts as the main controller to manage input/output and communicate with the camera and detection module.
- **Mobile App Integration**: Sends notifications and data to a mobile app (WildialApp) for remote monitoring.

## Components Used

- **Arduino Uno**: The central processing unit of the system.
- **Camera Module : For capturing live footage.
- **YOLO Algorithm**: For object detection and wildlife identification.
- **WildialApp**: A mobile application integrated with the system for alerts and real-time monitoring.


## How it Works

1. The camera captures video feeds, which are processed using the YOLO algorithm to detect wildlife.
2. The Arduino Uno handles communication between the camera module and the detection algorithm.
3. Once wildlife is detected, an alert is sent to the **WildialApp**.


## Requirements

- **Arduino Uno** board
- **Camera Module** 
- **YOLO model** for object detection
- **WildialApp** for mobile notification integration


## Setup Instructions

1. **Install Required Libraries**:
   - Install the YOLO object detection model on your system.
   - Install necessary Arduino libraries to control the camera module.

2. **Connect Hardware**:
   - Connect the camera module to the Arduino Uno.


3. **Upload Code to Arduino**:
   - Upload the provided Arduino code to your Arduino Uno.

4. **Run the YOLO Model**:
   - Ensure the YOLO model is running and connected to the system for real-time detection.

5. **Mobile App Integration**:
   - Follow the integration steps for the **WildialApp** to receive notifications.



