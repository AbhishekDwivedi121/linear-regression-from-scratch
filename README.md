# Linear Regression From Scratch

## Overview
This project demonstrates the implementation of Linear and Multiple Linear Regression completely from scratch, without using any machine learning libraries like Scikit-Learn. The goal is to understand the mathematical concepts, gradient descent optimization, and key ideas such as multicollinearity and bias-variance tradeoff using pure Python.

## Objectives
- Implement Simple Linear Regression manually.
- Extend it to Multiple Linear Regression.
- Build Gradient Descent algorithm from scratch.
- Detect and handle Multicollinearity.
- Understand Bias-Variance Tradeoff.
- Evaluate model using manual error metrics.

## Mathematical Concepts
**Hypothesis Function:**  
y = b0 + b1*x1 + b2*x2 + ... + bn*xn

**Cost Function (MSE):**  
J(θ) = (1 / 2m) * Σ(y_pred - y_true)²

**Gradient Descent Update Rule:**  
θj := θj - α * ∂J(θ) / ∂θj

## Features Implemented
- Manual data normalization and scaling.
- Gradient Descent algorithm with cost convergence visualization.
- Residual and error analysis.
- Multicollinearity detection using correlation.
- Bias-Variance analysis using custom data.

## Evaluation Metrics
All metrics are calculated manually:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Structure
linear-regression-from-scratch/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   ├── 01_simple_linear_regression.ipynb
│   ├── 02_multiple_linear_regression.ipynb
│   └── 03_gradient_descent.ipynb
│
├── src/
│   ├── linear_regression.py
│   ├── gradient_descent.py
│   ├── metrics.py
│   └── utils.py
│
├── visuals/
│   └── loss_curve.png
│
└── README.md

## Overview of Work
This repository will continuously expand to include all topics related to regression — including handling of multicollinearity, bias-variance tradeoff, gradient-based optimization methods, and other advanced regression concepts like polynomial and regularized regression. The goal is to build every concept from scratch to deeply understand how regression models work mathematically and programmatically.
