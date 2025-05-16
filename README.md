# Breast Cancer Classification Model Evaluation

This repository contains a Jupyter notebook demonstrating the evaluation of a machine learning classification model applied to the breast cancer dataset. The notebook walks through data preprocessing, model training using a Decision Tree classifier, and detailed performance evaluation.

## Contents

- Data loading and preprocessing (standardization)
- Splitting data into training and testing sets
- Training a Decision Tree classifier
- Model prediction and accuracy calculation
- Detailed evaluation using:
  - Confusion matrix visualization
  - Classification report (precision, recall, f1-score, support)
  - Calculation of key metrics (accuracy, precision, recall, F1 score)

## About the Evaluation Metrics

- **Accuracy**: Overall correctness of the model.
- **Precision**: How many selected items are relevant (important when false positives are costly).
- **Recall**: How many relevant items are selected (important when false negatives are costly).
- **F1 Score**: Harmonic mean of precision and recall, balancing the two.

## Classification Report

The classification report provides detailed performance metrics for each class in the dataset:

- **Precision**: Of all instances predicted as a class, how many were correct.
- **Recall**: Of all actual instances of a class, how many were correctly identified.
- **F1-score**: The harmonic mean of precision and recall, providing a single metric for model performance.
- **Support**: The number of actual occurrences of each class in the test set.

This report helps to understand the model’s strengths and weaknesses for each class individually.

## Confusion Matrix

The confusion matrix visually summarizes the model's performance by showing the counts of:

- True Positives (correct positive predictions)
- True Negatives (correct negative predictions)
- False Positives (incorrect positive predictions)
- False Negatives (incorrect negative predictions)

This helps identify specific types of classification errors.

