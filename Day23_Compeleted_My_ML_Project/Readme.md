# Day 23 – House Price Prediction Project Completion

Today, I completed my **House Price Prediction** machine learning project. The objective was to predict **median house prices** using various housing-related features from the California Housing dataset.

## Project Title

**House Price Prediction**

---

## Project Objective

The aim of this project was to build a regression model capable of predicting house prices based on features such as location, population, number of rooms, households, and other housing attributes.

---

## Work Completed

### 1. Loading the Dataset

- Loaded the California Housing dataset using Pandas.
- Explored the dataset to understand its structure.

---

### 2. Feature Selection

To improve the model, unnecessary columns were removed before training.

Examples include:

- `median_income`
- Other non-required features used during experimentation

---

### 3. Splitting the Dataset

The dataset was divided into:

- **Training Set (80%)**
- **Testing Set (20%)**

using Scikit-learn's `train_test_split()` function.

---

### 4. Handling Missing Values

Missing values in the **total_bedrooms** column were handled using **SimpleImputer** with the **median** strategy.

---

### 5. Feature Scaling

The numerical features were standardized using **StandardScaler** before training the model.

---

### 6. Model Selection

The project uses a **Random Forest Regressor** for predicting house prices.

### Advantages

- Handles non-linear relationships effectively.
- Reduces overfitting using multiple decision trees.
- Provides accurate predictions for regression tasks.

---

### 7. Model Evaluation

The trained model was evaluated using the **R² Score** to measure prediction accuracy.

---

## Machine Learning Workflow Followed

1. Collected the dataset.
2. Explored the dataset.
3. Removed unnecessary features.
4. Handled missing values.
5. Applied feature scaling.
6. Split the dataset.
7. Trained the Random Forest Regressor.
8. Evaluated the model using the R² Score.

---

## What I Learned Today

- Completed an end-to-end regression project.
- Performed feature selection and preprocessing.
- Handled missing values using **SimpleImputer**.
- Applied **StandardScaler** for feature scaling.
- Trained a **Random Forest Regressor**.
- Evaluated the model using the **R² Score**.
- Understood the complete workflow of a machine learning regression project.