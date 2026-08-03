# Day 25 – CNN Image Classification Implementation

Today, I implemented a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** for a **Cat vs Dog image classification** task. I learned the complete workflow of loading image datasets, preprocessing images, building a CNN architecture, and training it for binary classification.

## Topics Learned

- Image Dataset Loading
- Image Preprocessing
- Image Normalization
- Conv2D Layer
- Batch Normalization
- Max Pooling
- Flatten Layer
- Dense Layers
- Dropout
- Binary Classification
- Model Compilation
- Model Training

---

## Project Overview

The objective was to classify images into two categories:

- Cat
- Dog

The dataset was divided into training and validation sets before model training.

---

## Image Preprocessing

Before training the model:

- Loaded images directly from folders.
- Normalized pixel values between **0 and 1**.
- Prepared the dataset for efficient training.

---

## CNN Architecture

The model consisted of:

- Three Convolution Layers
- Three Batch Normalization Layers
- Three Max Pooling Layers
- Flatten Layer
- Dense Layers
- Dropout Layer
- Output Layer with **Sigmoid** activation

---

## Model Training

The CNN was compiled using:

- **Adam Optimizer**
- **Binary Crossentropy** Loss
- **Accuracy** Metric

The model was then trained using the training dataset and validated on the validation dataset.

---

## What I Learned Today

- Loaded image datasets using TensorFlow.
- Performed image normalization.
- Built a CNN using the Sequential API.
- Used Conv2D, MaxPooling, BatchNormalization, Flatten, Dense, and Dropout layers.
- Trained a binary image classification model.
- Understood the complete CNN implementation workflow.