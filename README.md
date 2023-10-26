# Number Plate Recognition using YOLOv5

## Overview

This project employs YOLOv5, a state-of-the-art object detection model, for the task of recognizing number plates in images. The dataset used for training is annotated using LabelImg, a graphical image annotation tool.

## Getting Started

### Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- **Python 3.x:** The programming language used for the project.
- **PyTorch:** An open-source machine learning library.
- **OpenCV:** A library for computer vision and image processing.
- **YOLOv5:** The version 5 of the You Only Look Once (YOLO) object detection model.
- **LabelImg:** A graphical image annotation tool.

## How It Works (Brief Theory)

### YOLOv5

YOLOv5 is an object detection model dividing an image into a grid, predicting bounding boxes and class probabilities for objects in each grid cell. Designed for real-time object detection.

### LabelImg

LabelImg is a graphical image annotation tool streamlining manual annotation for object detection. Users draw bounding boxes around objects, and annotations are saved in YOLO format.

### Training

Training involves feeding annotated data into YOLOv5. The model adjusts parameters to predict bounding boxes and class labels accurately. Trained weights are saved for later inference.

### Inference

Inference uses the trained model to predict on new images. `detect.py` runs inference on specified images, utilizing the trained YOLOv5 model.

