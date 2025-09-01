# Ridge Regression (L2 Regularization) – From Scratch & Using Scikit-Learn
## Overview

This repository demonstrates the implementation of Ridge Regression, a form of Linear Regression with L2 regularization. It includes:

A theoretical introduction to L2 Regularization

Ridge Regression implemented from scratch (gradient descent)

Ridge Regression using Scikit-Learn

Model evaluation using the R² score

## What is L2 Regularization (Ridge Regression)?	

Ridge Regression modifies this by adding an L2 penalty:

λ (lambda) is the regularization parameter:

λ = 0 → equivalent to Linear Regression

Higher λ → shrinks coefficients, reduces overfitting​

# Repository Structure

## 1. Ridge_Regularization_ipynb.ipynb
Loads the Breast Cancer dataset (sklearn.datasets)

Trains Ridge Regression using Scikit-Learn

Compares results with and without regularization

Evaluates using R² score & RMSE

## 2. ridge_regression_from_scratch_m_and_b_ipynb.ipynb

Generates a synthetic dataset (make_regression)

Implements Ridge Regression from scratch (manual gradient descent)

Visualizes dataset and fitted line

Shows effect of different λ values

## 3. ridge_regression_from_scratch.ipynb

Loads the Breast Cancer dataset

Implements Ridge Regression manually

Makes predictions and evaluates using R² score

# Model Evaluation – R² Score

The R² score measures how well the model explains variance in the target

R² = 1 → Perfect fit

R² = 0 → Model is no better than mean prediction

Negative R² → Model worse than a baseline

Ridge (Sklearn – Breast Cancer dataset)

Without Ridge → 0.63

With Ridge → 0.74

Ridge (From Scratch – Synthetic dataset) → 0.92

Ridge (From Scratch – Breast Cancer dataset) → 0.74

✅ Higher R² means Ridge improved generalization compared to standard Linear Regression.


# How to Run

git clone https://github.com/Vivekk-007/Ml.git

cd "Ml/Ridge (L2)Regularization"
jupyter notebook




# Key Learnings

Ridge Regression reduces overfitting by penalizing large coefficients.

Implementing from scratch builds understanding of gradient descent.

The R² score is a key metric for regression model performance.



