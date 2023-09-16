# Computer Vision with OpenCV

This repository contains examples of computer vision tasks using the OpenCV library. It demonstrates face detection and background blur as well as calculating the distance of a detected face from the camera.

## Face Detection with Background Blur

### `blurBackground.ipynb`

This Jupyter Notebook demonstrates how to perform face detection and apply background blur using OpenCV.

#### How the Code Works

The code does the following:

1. Initializes the webcam for capturing video.
2. Detects faces in the video feed using the Haar Cascade classifier.
3. Applies Gaussian blur to the background while keeping the detected face sharp.
4. Displays the video feed with face detection and background blur.
5. Press 'q' to exit the program.

#### Usage

1. Make sure you have OpenCV installed: `pip install opencv-python`.

2. Run the Jupyter Notebook using a compatible environment.

3. The notebook will open your webcam feed with face detection and background blur.

## Calculating Distance of Face from Camera

### `distanceOfFaceFromCamera.ipynb`

This Jupyter Notebook demonstrates how to calculate the distance of a detected face from the camera using OpenCV.

#### How the Code Works

The code does the following:

1. Initializes the webcam for capturing video.
2. Detects faces in the video feed using the Haar Cascade classifier.
3. Estimates the distance of the detected face from the camera based on size.
4. Displays the estimated distance on the video feed.
5. Press 'q' to exit the program.

#### Usage

1. Make sure you have OpenCV installed: `pip install opencv-python`.

2. Run the Jupyter Notebook using a compatible environment.

3. The notebook will open your webcam feed with face detection and estimated distance display.
