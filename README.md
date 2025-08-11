# Intelligent Driver Assistance through AI-based Lane and Object Detection System
 

Welcome to my project repository where I explore advanced computer vision techniques to develop an integrated lane and object detection system.  
This project leverages the power of the **OpenCV** library and the **YOLO** (You Only Look Once) object detection model to identify and visualize driving lanes and objects in real-time video feeds via a Flask-based web interface.

---

## Project Overview
This system combines two crucial aspects of autonomous driving technologies:

- **Lane Detection**: Detects driving lanes using image processing techniques.
- **Object Detection**: Identifies road objects in real-time using a YOLO model fine-tuned for vehicle detection.

The goal is to create a robust tool that can aid in the development of intelligent driver assistance systems by providing real-time navigational assistance through lane and object recognition.

---

## Features
- **Real-Time Lane Detection**: Utilizes Canny Edge Detection and Hough Transform to detect and highlight lanes on the road.
- **Object Detection with YOLO**: Detects vehicles and other road objects with high accuracy using a pre-trained YOLO model.
- **Web Interface**: Flask-powered front-end for uploading videos and viewing processed results.
- **Frame-by-Frame Processing**: Combines lane and object overlays into a single visual output.
- **Flexible Video Input**: Works with uploaded `.mp4` videos of various resolutions.

---

## Technologies Used
- **Python**: All back-end code is written in Python 3.8+.
- **OpenCV (cv2)**: Used for all image processing operations, including video capture, Canny edge detection, ROI masking, and drawing utilities.
- **NumPy**: Handles all array operations and mathematical computations efficiently.
- **YOLO (Ultralytics)**: Implements object detection using a fine-tuned YOLO model with pre-trained weights.
- **Flask**: Serves as the web application framework for user interaction.
- **Pathlib & Tempfile**: For cross-platform file path management and temporary file handling.

---

## Getting Started
To run this project locally, follow these steps:

### Prerequisites
- Python 3.8 or above
- OpenCV
- NumPy
- Flask
- Ultralytics YOLO package

---

### Installation
Install the required packages:
```bash
pip install -r requirements.txt
```
### Usage
To start the detection system, run the script from your command line:
```bash
python app.py
```
Make sure to replace app.py with the actual path to the Python script if not running from the script's directory.
