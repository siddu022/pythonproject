# pythonproject


# Face Recognition App Lock

This project is an academic exercise demonstrating the implementation of a face recognition-based application lock using Python and OpenCV.

## Overview

The face recognition app lock is designed to allow access to certain functionalities or resources only to authorized users whose faces are recognized by the system. It captures images from the webcam, detects faces, and compares them with the pre-trained face recognition model to determine if access should be granted.

## Features

- **Face Detection**: Utilizes Haar cascade classifiers to detect faces in real-time webcam input.
- **Face Recognition**: Trains a LBPH face recognition model using captured images of authorized users.
- **User Authentication**: Grants access if the detected face matches an authorized user's face with a confidence level above a certain threshold.
- **Web Browser Integration**: Opens a specified web browser upon successful face recognition.

## Dependencies

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

## Usage

1. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/siddu022/pythonproject.git
