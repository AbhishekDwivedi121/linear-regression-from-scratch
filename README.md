# Linear Regression From Scratch

## Overview
This project presents a complete mathematical and programmatic implementation of Linear and Multiple Linear Regression from scratch, without using any pre-built machine learning libraries. It explores not only prediction but also the statistical and inferential aspects of regression in depth.

## Objectives
- Implement Simple and Multiple Linear Regression manually.
- Build Gradient Descent optimization from scratch.
- Analyze Multicollinearity and understand its impact on inference.
- Explore Bias-Variance Tradeoff.
- Perform model evaluation using both manual and statistical methods.
- Deeply study regression assumptions and their effects on results.

## Mathematical Concepts
**Hypothesis Function:**  
y = b0 + b1*x1 + b2*x2 + ... + bn*xn  

**Cost Function (MSE):**  
J(θ) = (1 / 2m) * Σ(y_pred - y_true)²  

**Gradient Descent Update Rule:**  
θj := θj - α * ∂J(θ) / ∂θj  

## Features Implemented
- Manual implementation of Linear and Multiple Regression.
- Gradient Descent algorithm with visualization of loss convergence.
- Handling and analysis of Multicollinearity.
- Bias-Variance analysis with controlled datasets.
- Manual computation of model evaluation metrics (MAE, MSE, RMSE, R²).
- Calculation of **TSS (Total Sum of Squares)**, **RSS (Residual Sum of Squares)**, and **ESS (Explained Sum of Squares)**.
- Understanding why multicollinearity doesn’t affect prediction but impacts inference and coefficient interpretation.

## Statistical Analysis
- Performing **t-tests**, **F-tests**, and statistical validation similar to `statsmodels.summary()`.
- Evaluating model parameters, significance levels, and confidence intervals.
- Checking assumptions such as:
  - Linearity
  - Independence
  - Homoscedasticity
  - Normality of residuals
  - No multicollinearity

## Advanced Work
This project will be continuously expanded to include:
- **Ridge** and **Lasso Regression** implementations from scratch.
- Deeper exploration of **regularization techniques**.
- Statistical inference for model comparison.
- Visualization and interpretation of regression diagnostics.

## Goal
To build a complete regression framework from scratch — combining mathematical derivation, programming logic, and statistical reasoning — enabling a full understanding of how linear models truly work from data generation to inference and prediction.
