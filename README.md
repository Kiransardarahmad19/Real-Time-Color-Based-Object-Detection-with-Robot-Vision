# Real-Time-Color-Based-Object-Detection-with-Robot-Vision

This project implements a real-time color-based object detection system using OpenCV and Python. The program captures live video from a camera, processes each frame to detect specific color-based objects, and marks their centroids for further use in robotics applications. An interactive HSV control window allows the user to fine-tune color detection parameters dynamically.

This project leverages computer vision techniques to detect objects based on a specified color range in the HSV color space. The program identifies and tracks the centroid of the largest color-matching region within each frame. This could be useful for a variety of robotics tasks, such as following a color-coded object or identifying specific areas in a controlled environment.

#Features

### 1. Real-Time Color Detection
Detects objects based on color from a live camera feed.
### 2. Centroid Tracking
Calculates and marks the centroid of the detected object.
### 3. Interactive HSV Control
A trackbar window for adjusting HSV color thresholds, allowing fine-tuning for optimal color detection.
