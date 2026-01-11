## Overview

This project implements a real-time face detection and tracking system using MATLAB.
The system captures live video from a webcam, detects human faces in each frame, and continuously tracks them in real time.

The project demonstrates practical application of computer vision techniques for object detection and real-time video processing. 
## Objectives
Capture live video input using a webcam

Detect human faces in real-time

Track detected faces across consecutive frames

Display bounding boxes around detected faces

Implement a real-time computer vision pipeline



## Technologies Used

MATLAB

Image Processing Toolbox

Computer Vision ToolboxMethodology

Initialize webcam and video input

Load pre-trained face detection model

Capture video frames in real time

Convert frames to suitable format for detection

Detect faces using MATLAB’s built-in detector

Draw bounding boxes around detected faces

Continuously update detection for live tracking
## Face Detection Technique

Viola–Jones based face detection

Uses Haar-like features and cascade classifiers

Optimized for real-time performance
## Features

Real-time webcam video processing

Automatic face detection

Continuous face tracking

Bounding box visualization

Lightweight and efficient execution

## Limitations

Performance depends on lighting conditions

Accuracy reduces with occlusions or side faces

Tracks faces frame-by-frame without identity recognition

## Future Improvements

Add face recognition functionality

Improve robustness under low-light conditions

Implement multi-face identity tracking

Integrate deep learning–based detectors

Optimize for higher frame rates