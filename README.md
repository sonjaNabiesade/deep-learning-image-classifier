# CNN Image Classification: Tom vs Jerry
## Overview

This project implements a convolutional neural network (CNN) to perform binary image classification, distinguishing between cartoon characters Tom and Jerry. The aim was to explore the full deep learning pipeline including preprocessing, model architecture design, training, and evaluation.

### Dataset

3,187 RGB images

Two classes: Tom and Jerry

Train/validation split: 80/20

### Model Architecture

Conv2D layers (32, 64, 128 filters)

MaxPooling layers

Dense(128) fully connected layer

Dropout (0.5) for regularisation

Sigmoid output for binary classification

### Techniques Used

Image resizing (128x128)

Normalisation

Data augmentation (flip, rotation, zoom)

Adam optimiser

Binary cross-entropy loss

### Results

Validation accuracy ≈ 96%

Balanced precision, recall, and F1-score

Effective generalisation with minimal overfitting.

### Technologies

Python

TensorFlow / Keras (if used)

NumPy

Matplotlib
