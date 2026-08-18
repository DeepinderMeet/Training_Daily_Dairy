# Day 21 – Perceptron and Artificial Neural Network (ANN)

Today, I implemented a **Perceptron** and an **Artificial Neural Network (ANN)** using the **Iris dataset**. I learned how to preprocess data, encode target labels, scale features, train classification models, evaluate their performance, save trained models, and use them for predictions.

## Topics Learned

- Iris Dataset
- Data Preprocessing
- Label Encoding
- Feature Scaling
- Perceptron Classifier
- Artificial Neural Network (ANN)
- Dense Layers
- ReLU Activation
- Softmax Activation
- Model Training
- Model Evaluation
- Saving and Loading Models
- Prediction on New Data

---

## Dataset

The **Iris dataset** was used for a multi-class classification task, where the target variable contains three different flower species.

---

## Data Preprocessing

Before training the models, I:

- Separated input features and target labels.
- Encoded categorical labels.
- Split the dataset into training and testing sets.
- Standardized the numerical features.

---

## Perceptron

A **Perceptron** classifier was trained using Scikit-learn and evaluated using **Accuracy Score** and **Classification Report**.

---

## Artificial Neural Network (ANN)

A simple ANN was built using TensorFlow's **Sequential** model with:

- Input Layer
- Hidden Layers (16 and 8 neurons)
- Output Layer (3 neurons)

The model used **ReLU** for hidden layers, **Softmax** for the output layer, **Adam** optimizer, and **Categorical Crossentropy** loss. After training for **100 epochs**, the model was evaluated, saved, reloaded, and tested on new flower samples.

---

## What I Learned Today

- Implemented a Perceptron classifier.
- Built an ANN using TensorFlow/Keras.
- Applied Label Encoding and StandardScaler.
- Trained and evaluated classification models.
- Saved and loaded trained models.
- Predicted the class of new input samples.