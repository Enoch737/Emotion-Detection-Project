
# Emotion Detection Using Convolutional Neural Networks

## Executive Summary

This project demonstrates a deep learning approach to facial emotion recognition using the FER-2013 dataset. With convolutional neural networks (CNNs), we trained a model to identify emotions such as happiness, anger, sadness, and surprise from facial expressions captured in 48x48 grayscale images.

## Dataset Overview

- Source: Kaggle (FER-2013)
- Size: ~35,000 labeled images
- Classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
- Format: CSV with pixel values and labels

## Objectives

- Build a robust CNN-based classifier for emotion detection
- Improve model accuracy through data augmentation
- Enable predictions on unseen facial images

## Methodology

1. **Data Preparation**  
   - Load and preprocess images  
   - Normalize pixel values  
   - Split into training, validation, and test sets

2. **Model Architecture**  
   - 4 Convolutional layers with ReLU + MaxPooling  
   - Dropout and BatchNormalization  
   - Dense output layer with softmax (for 7 emotion classes)

3. **Training**  
   - Loss Function: Categorical Crossentropy  
   - Optimizer: Adam  
   - Epochs: 50  
   - Data Augmentation: Applied via `ImageDataGenerator`

4. **Evaluation**  
   - Accuracy: ~91%  
   - Confusion Matrix and Classification Report  
   - Emotion predictions on test images

## Conclusion

This CNN-based model achieved high accuracy in detecting emotions from facial expressions. This technology has real-world applications in customer service bots, mental health monitoring, and social media sentiment analysis.

## Future Improvements

- Use transfer learning with pre-trained models (e.g., VGG, ResNet)
- Increase dataset diversity
- Deploy model as an API or web app for real-time inference

## References

- Kaggle FER-2013 Dataset: https://www.kaggle.com/datasets/msambare/fer2013  
- TensorFlow/Keras Documentation: https://www.tensorflow.org/  
- Facial Expression Recognition Research Papers
