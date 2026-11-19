# Computer Vision – Image Processing and Object Detection

## Project Overview

This project explores classical computer vision techniques and deep learning-based detection using OpenCV 5.0, YuNet and YOLOv8.

The objective is to understand image processing operations, analyse image features, detect human faces and identify multiple objects in images and videos.

## Technologies Used

- Python
- OpenCV 5.0
- NumPy
- Matplotlib
- Ultralytics YOLOv8
- YuNet Face Detection
- Google Colab

## Installation and Setup

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Import the required libraries:

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
from ultralytics import YOLO
```

## Project Tasks

### Task 1: Morphological Operations

Implemented four morphological operations:
- Erosion
- Dilation
- Opening
- Closing

Compared different kernel shapes and sizes to understand image noise removal and processing.

### Task 2: Bitwise Operations and Histograms

Implemented:
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- Bitwise NOT

Studied grayscale and colour histograms, brightness adjustment and contrast enhancement.

### Task 3: Face Detection Using YuNet

Implemented YuNet face detection using OpenCV.

- Detected faces in different images.
- Displayed facial landmarks and confidence scores.
- Compared different confidence thresholds.
- Applied Gaussian blur for face anonymisation.

### Task 4: Object Detection Using YOLOv8

Implemented YOLOv8 Nano for object detection.

- Detected multiple objects in images.
- Processed a sample video.
- Compared confidence and IoU thresholds.
- Analysed per-class object detection results.

### Task 5: Integrated Computer Vision Pipeline

Combined YuNet face detection and YOLO object detection in a single video pipeline.

- Combined face and object detection.
- Applied morphological pre-processing.
- Benchmarked FPS performance.
- Prepared a final comparison table.

## Results and Visualizations

All generated plots and result images are available in the `plots` folder.

Important visualizations include:

- Morphological operation comparisons
- Histogram comparisons
- Face detection results
- YOLO object detection results
- FPS comparison chart
- Final results comparison table

## Models and References

- YuNet Face Detection: https://github.com/opencv/opencv_zoo
- YOLOv8 Documentation: https://docs.ultralytics.com/
- OpenCV Documentation: https://docs.opencv.org/

## Video Demonstration

Video Link: **[Add your demonstration video link here]**

## Conclusion

This project demonstrates the combination of classical image processing techniques and deep learning-based detection methods.

It provides practical experience in image analysis, face detection, object detection, video processing and performance evaluation using computer vision technologies.

## Author

Computer Vision Practical 3 Project
