# Emotion Detection from Facial Expressions

![Made with Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Built with TensorFlow](https://img.shields.io/badge/Built%20with-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

[![Open In Colab](https://colab.research.google.com/github/Enoch737/Emotion-Detection-Project/blob/main/Emotion_Detection_Cleaned.ipynb)](https://colab.research.google.com/github/Enoch737/Emotion-Detection-Project/blob/main/Emotion_Detection_Cleaned.ipynb)

---

## Project Summary

This project implements a CNN (Convolutional Neural Network) to detect emotions in facial expressions using the FER-2013 dataset. The model was trained using TensorFlow and achieves ~91% accuracy.

## Files Included

- `Emotion_Detection_Cleaned.ipynb` — Polished Jupyter notebook
- `Emotion_Detection_Report.md` — Full project report
- `emotion_detection_preview.png` — Sample confusion matrix

## Dataset

- Source: [Kaggle FER-2013 Dataset](https://www.kaggle.com/datasets/msambare/fer2013)
- Format: CSV with 48x48 pixel grayscale images and emotion labels
- Emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Seaborn, Matplotlib

## Model Overview

- Architecture: CNN with Conv2D, MaxPooling, Dropout, BatchNorm
- Output Layer: Softmax for 7 classes
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Accuracy: 91%

## Author

**Enoch Narteh-Kofi**  
Student of Master of Financial Innovation and Technology  
Smith School of Business, Queen’s University, Canada

---

👉 [Read the full project report here](Emotion_Detection_Report.md)
