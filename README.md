# SSD300 Real-Time Object Detection

This project implements the **SSD300 (Single Shot Multibox Detector)** for real-time object detection
using TensorFlow and Keras. SSD is a fast and efficient deep learning model that can detect objects 
in images and video streams with high accuracy.

## Source 
- The project is based on the model in https://github.com/pierluigiferrari/ssd_keras/ abd paper 

## Features
- **Real-Time Object Detection**: Designed for high-speed detection from live video feeds (e.g., webcam).
- **Customizable**: Easily adjust parameters like aspect ratios, variances, and scales for anchor boxes.
- **Extensible**: Can be fine-tuned for custom datasets and applications.

---

## Requirements
- Python 3.7
- TensorFlow 1.x (1.15 recommended)
- OpenCV (for video and image handling)

## Use
-Put the weights `VGG_VOC0712_SSD_300x300_iter_120000.h5` into the folder `\weights` 
- python ssd300_webcam.py
