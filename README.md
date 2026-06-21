# Emotion Detection using MediaPipe and FACS

This project implements a real-time facial emotion detection system using MediaPipe Face Landmarker and principles inspired by Paul Ekman's Facial Action Coding System (FACS). The application uses webcam input to track facial landmarks and classify emotions based on rule-based analysis of facial features.

## Features

* Real-time webcam-based emotion detection
* Detects Happy, Angry, Surprised, and Neutral expressions
* Facial landmark tracking using MediaPipe
* Rule-based emotion classification
* Visual display of tracked facial features and live metrics

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy

## Installation

```bash
pip install opencv-python mediapipe numpy
```

## Running the Project

```bash
python emotiondetector.py
```

## How It Works

The system tracks key facial landmarks and calculates metrics such as:

* Mouth width
* Mouth openness
* Eye openness
* Brow-to-eye distance

These measurements are evaluated using predefined rules inspired by FACS to classify facial expressions into different emotions.

## Future Improvements

* Support for additional emotions
* Machine learning-based emotion classification
* Improved accuracy through calibration and normalization
* Performance optimization for deployment

## Author
Kimayayaya
