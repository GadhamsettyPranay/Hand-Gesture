# Hand Gesture Recognition using OpenCV and MediaPipe

This project focuses on real-time hand gesture recognition using a webcam. It uses OpenCV for video capture and display, and MediaPipe for detecting and analyzing hand landmarks. The goal is to identify how many fingers are raised and classify simple gestures.

## Features

- Real-time webcam-based hand tracking  
- Detection of 21 hand landmarks  
- Finger state identification (raised or not)  
- Basic gesture classification (0 to 5 fingers)  
- Visual feedback with annotations on video stream  

## Technologies Used

- Python  
- OpenCV  
- MediaPipe  
- NumPy  

## How It Works

The system captures video frames from your webcam, detects a hand using MediaPipe’s hand tracking solution, and identifies the position of each finger. Based on the relative position of the landmarks, it determines which fingers are open or closed and classifies the gesture accordingly. For example, showing 2 fingers corresponds to a “peace” gesture.

## Applications

- Gesture-based user interfaces  
- Touchless control systems  
- Sign language interpretation (basic)  
- Interactive games  

## Requirements

- A webcam for capturing video input  
- A Python environment with required libraries (OpenCV, MediaPipe, NumPy)  

## Future Scope

- Integrating more complex gestures  
- Controlling applications (e.g., volume, media, cursor)  
- Enhancing accuracy for different lighting conditions and backgrounds  
- Two-hand gesture support  

## Author

**Pranay Kumar Gadhamsetty**
