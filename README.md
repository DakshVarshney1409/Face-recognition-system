# Face Recognition System

This repository contains the code for a Face Recognition System built using Python, OpenCV, and Haarcascades. The system captures images from a webcam, detects faces, and recognizes them using a classification algorithm.

## Installation

To set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Face-Recognition-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Face-Recognition-System
    ```
3. Install the required packages:
    ```bash
    pip install numpy opencv-python os
    ```

## Usage

### 1. Capture Images and Generate Training Data

Run the script to capture images and generate training data:

```bash
python face_data_collect.py
```

### 2. Recognise Faces

Run the script to recognize faces in a video stream:

```bash
python face_recognition.py
```
