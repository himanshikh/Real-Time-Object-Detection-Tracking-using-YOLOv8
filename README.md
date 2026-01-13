# Real-Time Object Detection & Tracking using YOLOv8

## Overview
This project implements a real-time object detection and multi-object tracking system using a pre-trained YOLOv8 model. The application processes a live webcam feed, detects objects in each frame, and assigns unique tracking IDs to consistently follow objects across consecutive frames.

YOLOv8’s built-in tracking mechanism (based on SORT-like algorithms) enables efficient and accurate real-time tracking.

## Features
- Real-time object detection using YOLOv8
- Multi-object tracking with unique persistent IDs
- Live webcam video processing using OpenCV
- Visualization of bounding boxes, class labels, confidence scores, and tracking IDs

## Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Computer Vision
- SORT-based Object Tracking

## Install Dependencies
pip install ultralytics opencv-python

##Output
Live webcam feed with:
Detected objects
Bounding boxes
Class labels
Confidence scores
Unique tracking IDs

##Applications
Surveillance and security systems
Traffic and pedestrian monitoring
Autonomous driving perception
Smart retail analytics
Human activity analysis

##Future Enhancements
Support for custom-trained YOLO models
Save output as video files
Object counting and analytics
Improved tracking under occlusion
