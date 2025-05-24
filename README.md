# Sign Language Letter Recognition using MediaPipe and Machine Learning

This project enables recognition of sign language **letters** using a webcam. It uses [MediaPipe](https://mediapipe.dev) to detect hand landmarks and a **Random Forest** classifier to recognize letters from sign language in real time.

## ✨ Features

- Collect sign language letter data from webcam
- Extract hand landmarks with MediaPipe
- Train a machine learning model (Random Forest)
- Recognize letters in real-time from webcam feed
- Supports easy expansion for additional letters

## 🧰 Requirements

```bash
pip install opencv-python mediapipe scikit-learn matplotlib
