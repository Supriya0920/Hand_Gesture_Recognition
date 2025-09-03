Hand Gesture Recognition

 Project Overview
This project implements a **Hand Gesture Recognition System** that detects and classifies hand gestures using computer vision and machine learning.  
It can be applied to **human-computer interaction (HCI)**, **virtual mouse/keyboard control**, **sign language recognition**, and **gesture-based interfaces**.  

The system uses **image processing** to extract hand features and a trained **machine learning / deep learning model** to classify gestures.

 Tech Stack
  - Programming Language: Python  
  - Libraries & Frameworks:
  - OpenCV – for image processing & hand detection  
  - Mediapipe – for hand landmark detection  
  - NumPy, Pandas – data preprocessing  
  - Scikit-learn / TensorFlow / Keras – model training & prediction  
  - Dataset: Custom dataset of hand gesture images (collected or open-source)  

Repository Structure
Hand-Gesture-Recognition/
│-- data/ # Dataset (images or keypoints of hand gestures)
│-- models/ # Trained ML/DL models
│-- notebooks/ # Jupyter notebooks for experimentation
│-- src/ # Python scripts for preprocessing & training
│ │-- preprocess.py
│ │-- train.py
│ │-- recognize.py
│-- requirements.txt # Dependencies
│-- README.md # Project documentation
Clone this repository:
   ```bash
   git clone https://github.com/Supriya0920/Hand_Gesture_Recognition.git
   cd Hand-Gesture-Recognition
Features

Detects hand region in real-time using OpenCV + Mediapipe

Extracts 21 hand landmarks (fingers, joints, wrist)

Trains a classification model to recognize gestures

Works in real-time with webcam

Example Gestures

Thumbs Up

Thumbs Down

Victory

Wave

Open Palm

Future Improvements

Extend to American Sign Language (ASL) recognition

Improve accuracy with deep learning (CNN, LSTM)

Add support for gesture-controlled applications (media player, games, etc.)
