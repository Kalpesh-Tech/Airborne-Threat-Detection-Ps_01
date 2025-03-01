# AIRBORNE THREAT DETECTION IN SURVEILLANCE VIDEOS

## Overview
Airborne threats, such as drones or other flying objects, pose significant security risks in surveillance scenarios. This project aims to detect airborne threats using deep learning techniques. We collected a dataset from various platforms, applied data augmentation to improve detection accuracy, and trained a YOLOv8 model on Google Colab.

## Features
- **Dataset Collection**: Gathered data from multiple platforms like Kaggle, Roboflow, and others.
- **Data Augmentation**: Enhanced dataset quality through various augmentation techniques.
- **YOLOv8 Conversion**: Converted dataset into a YOLOv8-compatible format.
- **Model Training**: Trained the YOLOv8 model on Google Colab for efficient detection.
- **Real-time Surveillance**: Designed for integration with surveillance systems.

## Dataset Collection
We acquired datasets from various platforms, including:
- Kaggle
- Roboflow
- Open-source repositories
- Custom-labeled data

## Data Augmentation
To improve the model’s generalization and robustness, we applied:
- Rotation
- Scaling
- Flipping
- Brightness and contrast adjustments
- Noise addition

## Model Training
1. **Preprocessing**: Converted dataset annotations to YOLOv8 format.
2. **Training Setup**: Utilized Google Colab with GPU acceleration.
3. **Hyperparameter Tuning**: Adjusted learning rate, batch size, and augmentation parameters.
4. **Evaluation**: Measured accuracy, precision, recall, and loss metrics.

## Installation & Usage
### Prerequisites
- Python 3.8+
- PyTorch
- Ultralytics YOLOv8
- OpenCV
- Google Colab

## Contributors
- Prathmesh Dhone 
- Kalpesh Borse
- Pragati Gomare
- Sarthak Manmode

## Acknowledgments
We acknowledge open-source datasets and tools like Kaggle, Roboflow, and Ultralytics for making this research possible.
