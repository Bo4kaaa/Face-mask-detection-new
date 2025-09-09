<<<<<<< HEAD
# Face-mask-detection
Face mask detection
=======
---
title: Face Mask Detection
emoji: 😷
colorFrom: blue
colorTo: green
sdk: gradio
sdk_version: "4.39.0"
app_file: app.py
pinned: false
---

# 😷 Face Mask Detection  

A simple deep learning app that detects whether a person is **wearing a mask** or **not wearing a mask**.  

## 🚀 Features
- Upload an image and get instant prediction.  
- Use webcam for real-time mask detection.  
- Displays probabilities for both classes (`Mask`, `No Mask`).  
- Lightweight and easy to run locally.  

## 🧠 Model
- Built with **TensorFlow / Keras**.  
- CNN with 4 convolutional layers (32, 32, 64, 128).  
- Includes ReLU activation, Batch Normalization, MaxPooling, and Dropout.  
- Final Dense layer with Sigmoid for binary classification.  
- Achieved **~93% accuracy** on test data.  

## 📂 Dataset
- Trained on the **Kaggle Face Mask Dataset**.  
- Two classes:  
  - `With Mask`  
  - `Without Mask`  

>>>>>>> 2c7dca1 (First commit)
