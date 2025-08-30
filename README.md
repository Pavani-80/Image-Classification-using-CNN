# CIFAR-10 Image Classification using CNN

This repository contains a Convolutional Neural Network (CNN) implementation for image classification on the CIFAR-10 dataset using TensorFlow/Keras.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Usage](#usage)
- [Requirements](#requirements)
- [Future Work](#future-work)
- [Author](#author)

---

## Project Overview
The goal of this project is to classify images from the CIFAR-10 dataset into 10 classes, such as airplanes, cars, birds, and more, using a deep learning approach with CNNs.

---

## Dataset
- Dataset: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- Training images: 50,000
- Test images: 10,000
- Image size: 32x32 pixels, 3 color channels (RGB)
- Classes:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

---

## Features
- Preprocessing and normalization of images
- Data augmentation (rotation, flips, shifts) to improve model generalization
- Model checkpointing and early stopping
- Training/validation accuracy and loss visualization
- Evaluation on test set
- Prediction on new images

---

## Model Architecture
- Convolutional layers with ReLU activation
- Max Pooling layers
- Dropout for regularization
- Fully connected (Dense) layers
- Softmax output layer for classification

---

## Results
- Test Accuracy: ~77%
- Test Loss: 0.66
- Training and validation curves show convergence with minimal overfitting

---

