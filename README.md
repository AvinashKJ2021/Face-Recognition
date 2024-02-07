# Face Recognition Project

This project is designed for face recognition using OpenCV and scikit-learn (Python's machine learning library). It allows you to perform face detection, capture faces from live video, and recognize individuals based on pre-trained data.

## Features

- Face detection and recognition in real-time video streams.
- Capturing faces from live video for training the recognition model.
- Generating attendance reports based on recognized faces.

## Prerequisites

- Python 3.x
- OpenCV
- scikit-learn
- NumPy
- Pandas

## Installation

1. Clone this repository to your local machine:
2. Install the required dependencies:
3. Ensure that you have the necessary pre-trained XML files for face detection (e.g., haarcascade_frontalface_default.xml).

## Usage

- Run `add_faces.py` to capture face data and train the recognition model.
- Run `test.py` for live face recognition and attendance tracking.
- Press 'p' for taking attendance and a subsequent date wise record is created.
- Press 'q' for exit.
