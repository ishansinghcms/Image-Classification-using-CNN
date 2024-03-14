# Image Classification using Convolutional Neural Networks (CNN)

## Introduction

This project aims to classify images from the CIFAR-10 dataset into ten different classes using Convolutional Neural Networks (CNN). The CIFAR-10 dataset consists of 60,000 32x32 color images in ten classes, including airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## Dataset

The CIFAR-10 dataset is available through the TensorFlow `datasets` module. It contains separate training and test sets, with 50,000 and 10,000 images, respectively.

## Model Architecture

The CNN architecture used for image classification comprises the following layers:

- Convolutional layers with ReLU activation for feature extraction.
- MaxPooling layers for down-sampling and feature selection.
- Flatten layer to convert the 2D feature maps into a 1D vector.
- Fully connected layers for classification.

## Training and Evaluation

The model is trained on the training dataset using the Adam optimizer and sparse categorical cross-entropy loss function. It is trained for ten epochs with a batch size of 32. After training, the model's performance is evaluated on the test dataset to assess its accuracy and classification metrics.

## Results

The trained CNN model achieved an accuracy of approximately 69% on the test dataset. A detailed classification report is provided to evaluate precision, recall, and F1-score for each class and overall model performance.
