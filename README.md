# Number Plate Recognition using YOLOv5 and Flask

## Overview

This project combines YOLOv5, a real-time object detection model, with a Flask web application for number plate recognition. The dataset is annotated using LabelImg, and the app is run using `app.py`.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- **Python 3.x**
- **PyTorch**
- **OpenCV**
- **YOLOv5**
- **LabelImg**
- **Flask**


## How It Works

### YOLOv5

YOLOv5 divides an image into a grid, predicting bounding boxes and class probabilities for objects. Designed for real-time object detection.

### LabelImg

LabelImg streamlines manual annotation for object detection. Annotations are saved in YOLO format.

### Training

Feed annotated data into YOLOv5. The model adjusts parameters for accurate predictions. Trained weights are saved for later inference.

### Inference

The Flask app (`app.py`) runs inference on new images using the trained YOLOv5 model.

number-plate-recognition/
│
├── data/
│   ├── images/
│   └── labels/
│
├── templates/
│   └── index.html
│   └── layout.html
│
├── static/
│   └── models/
│            └── best.onnx
│   └── predict/
│   └── roi/
│   └── upload/
│
├── utils/
├── train.py
├── yolo_predictions.py
├── app.py
├── requirements.txt
└── README.md


