# Spectrogram-Based Infant Emotional State Recognition Using Deep CNN

## Overview

This project presents a **Deep Convolutional Neural Network (Deep CNN)** based system for automatic infant cry classification. The proposed system converts infant cry audio signals into spectrogram images using the **Short-Time Fourier Transform (STFT)** and classifies different infant emotional states using a Deep CNN model.

The objective is to assist parents, caregivers, and healthcare professionals by automatically recognizing the reason behind an infant's cry.

---

## Features

- Audio preprocessing and noise reduction
- Spectrogram generation using STFT
- Deep CNN-based emotion classification
- Training, validation, and testing pipeline
- Performance evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- Predict emotion from unseen infant cry audio

---

## Dataset

The project uses publicly available Kaggle infant cry datasets.

### Dataset 1

Classes:

- Belly Pain
- Burping
- Hungry
- Discomfort
- Tired

### Dataset 2

Classes:

- Belly Pain
- Hungry
- Discomfort
- Tired
- Scared
- Cold/Hot

## Project Workflow

```
Infant Cry Audio
        │
        ▼
Audio Preprocessing
        │
        ▼
Noise Removal & Standardization
        │
        ▼
       STFT
        │
        ▼
Spectrogram Generation
        │
        ▼
     Deep CNN
        │
        ▼
Emotion Classification

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Librosa
- OpenCV
- Matplotlib
- Scikit-learn

## Deep Learning Model

The proposed model is a Deep Convolutional Neural Network consisting of multiple:

- Convolution Layers
- ReLU Activation
- Max Pooling Layers
- Fully Connected Layers
- Softmax Output Layer

The CNN automatically learns discriminative features from spectrogram images without requiring manual feature engineering.

---

## Performance Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Training Loss
- Validation Loss
- Test Loss
- Classification report

## References

- Donate-a-Cry Dataset
- Kaggle Infant Cry Audio Corpus

## Authors

**Jada Akhil**

**Peddaboodhi Vaishnavi**

**P. Charan Goud**

Department of Electronics and Communication Engineering

Vardhaman College of Engineering

---

## License

This project is developed for academic and research purposes.
