# ResNet CIFAR-10 Image Classification

## Project Overview

This project implements a ResNet-inspired Convolutional Neural Network (CNN) using TensorFlow and Keras for image classification on the CIFAR-10 dataset. The objective was to understand and apply residual learning concepts introduced in the ResNet architecture while building an end-to-end deep learning pipeline.

The model uses residual connections, batch normalization, dropout, and data augmentation techniques to improve training stability and classification performance.

---

## Dataset

CIFAR-10 is a widely used benchmark dataset for image classification.

**Dataset Details:**
- 50,000 training images
- 10,000 test images
- 10 image categories
- Image size: 32 × 32 pixels

**Classes:**
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

## Model Architecture

The network follows a ResNet-style architecture consisting of:

- Data Augmentation Layer
- Initial Convolution Block
- Residual Block Stack (64 Filters)
- Max Pooling
- Residual Block Stack (128 Filters)
- Max Pooling
- Residual Block Stack (256 Filters)
- Global Average Pooling
- Dropout Layer
- Dense Output Layer (10 Classes)

Residual connections help improve gradient flow and enable deeper networks to train more effectively.

---

## Techniques Used

- Residual Learning (Skip Connections)
- Batch Normalization
- ReLU Activation
- Data Augmentation
- Dropout Regularization
- Early Stopping
- TensorFlow / Keras

---

## Results

| Metric | Value |
|----------|----------|
| Training Accuracy | 94.4% |
| Test Accuracy | 86.3% |

---

## Project Structure

## Project Structure

ResNet_CIFAR10/

- notebook.ipynb
- resnet_cifar10.keras
- README.md
- requirements.txt
- screenshots/
- Summary/
