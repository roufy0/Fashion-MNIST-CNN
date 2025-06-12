# CNN Classifier on Fashion MNIST 

This project implements a deep Convolutional Neural Network (CNN) using TensorFlow/Keras to classify clothing items from the Fashion MNIST dataset.

##  Model Overview

- Input: 28x28 grayscale images
- Layers:
  - Multiple Conv2D + BatchNorm + Activation (ReLU)
  - Global Average Pooling
  - Dense + Dropout
- Optimized with:
  - Categorical crossentropy
  - Adam optimizer
  - ReduceLROnPlateau
  - EarlyStopping

##  Dataset

Uses [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) — a dataset of 70,000 labeled images of clothing items across 10 categories.

## Features

-  CNN model architecture for image classification
-  Data augmentation using `ImageDataGenerator`
-  Learning rate scheduling with `ReduceLROnPlateau`
-  Early stopping to prevent overfitting
-  Visualizations for training and testing performance

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Matplotlib

