# BASIC_FACE_RECOGNITION_SYSTEM
## Welcome to the Basic Face Recognition System! This project utilizes Python and several powerful libraries, including OpenCV, NumPy, Pandas, and the face_recognition library, to create a simple yet effective face recognition system.

### Table of Contents
####    1. Features
####    2. Requirements
####    3. Installation
####    4. Usage
####    5. How It Works

## Features
Real-time face detection and recognition
Ability to recognize multiple faces
Simple command-line interface
Easy to extend and modify

## Requirements
To run this project, you need to have the following libraries installed:
    Python 3.x
    OpenCV
    NumPy
    Pandas
    face_recognition
    random
You can install the required libraries using pip:
    pip install opencv-python numpy pandas face_recognition

## Installation
Clone the repository:
    git clone https://github.com/yourusername/BASIC_FACE_RECOGNITION_SYSTEM.git
    cd BASIC_FACE_RECOGNITION_SYSTEM
Install the required libraries (as mentioned above).
Ensure you have a webcam connected to your computer for real-time face recognition.

## Usage
Prepare your dataset:
Create a folder named faces in the project directory.
Add images of the faces you want to recognize in the dataset folder. each image's name should be the name of the person .
faces/
    │   ├── Person1.jpg
    │   ├── Person2.jpg

Run the face recognition script:
    python face_recognition_system.py
The system will start the webcam and begin recognizing faces in real-time.

## How It Works
    Face Detection: The system uses OpenCV to detect faces in the video stream from the webcam.
    Face Encoding: The face_recognition library is used to encode the detected faces for comparison.
    Recognition: The system compares the encoded faces with the known faces in the dataset and identifies them.
