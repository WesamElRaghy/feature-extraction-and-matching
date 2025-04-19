# Object Detection using ORB Feature Matching

This project implements object detection in both static images and videos using ORB (Oriented FAST and Rotated BRIEF) feature matching with OpenCV. The system can detect objects in static images and track them in real-time video streams.

## Features

### Static Image Detection
- ORB feature detection and matching
- Homography-based object localization
- Visual feedback with matched features
- Error handling and validation
- Support for various image formats

### Video Object Tracking
- Real-time object tracking in video streams
- FPS (Frames Per Second) calculation and display
- Live visualization of matching points
- Support for both recorded videos and webcam input
- Efficient feature matching and tracking

## Requirements

```python
opencv-python>=4.5.0
numpy>=1.19.0
