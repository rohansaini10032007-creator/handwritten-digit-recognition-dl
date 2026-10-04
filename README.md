# Handwritten Digit Recognition using Deep Learning

## Project Overview

This project uses Deep Learning to recognize handwritten digits from 0 to 9.

The MNIST dataset is used to train a Convolutional Neural Network (CNN). The model learns patterns from handwritten digit images and predicts the correct digit.

## Objectives

- To understand the basic workflow of Deep Learning.
- To work with the MNIST handwritten digit dataset.
- To preprocess image data.
- To build and train a CNN model.
- To evaluate the performance of the trained model.
- To predict handwritten digits using the trained model.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Dataset

The project uses the MNIST dataset, which contains handwritten grayscale images of digits from 0 to 9.

- Training images: 60,000
- Testing images: 10,000
- Image size: 28 × 28 pixels
- Number of classes: 10

## Model

A Convolutional Neural Network (CNN) is used for classification.

The model contains:

- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layers
- Softmax output layer

## Results

The trained model achieved a test accuracy of approximately **99.01%** on the MNIST test dataset.

The project also includes graphs showing training and validation accuracy and loss, along with sample predictions comparing actual and predicted digits.

## Project Structure

```text
handwritten-digit-recognition-dl/
│
├── Handwritten_Digit_Recognition_DL.ipynb
└── README.md
