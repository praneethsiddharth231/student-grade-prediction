# Student Final Grade Prediction

## Overview
A machine learning project that predicts students' final grades (G3) using their second-period grades (G2).

## Dataset
- Source: UCI Student Performance dataset
- Records: 649 students
- Input feature: G2
- Target variable: G3

## Methodology
- Exploratory Data Analysis (EDA)
- Train-test split
- Simple linear regression implemented from scratch
- Gradient descent for parameter optimization
- Model evaluation on unseen test data

## Results

| Metric | Value |
|---|---:|
| MAE | 0.729 |
| RMSE | 1.130 |
| R² Score | 0.869 |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn (for data splitting and evaluation)

## Limitations
The model uses only G2 to predict G3. These grades are strongly related, and results may vary with a different train-test split.

## What I Learned
- Linear regression
- Gradient descent
- Training and testing datasets
- Model evaluation metrics
