# SC5002 Lab Assignment

## Overview

This repository contains the machine learning experiments for the SC5002 Artificial Intelligence Fundamentals & Applications Lab Assignment at Nanyang Technological University.

## Dataset

California Housing Dataset from Scikit-Learn.

## Methods

- Linear Regression
- Ridge Regression
- StandardScaler
- 5-Fold Cross-Validation

## Experiments

Ridge Regression was evaluated using three regularization strengths:

- Alpha = 0.1
- Alpha = 10.0
- Alpha = 1000.0

Model performance was compared using the mean 5-fold cross-validation R² score.

## How to Run

1. Open `SC5002_Lab_Assignment.ipynb` in Google Colab.
2. Run the notebook cells sequentially.
3. Review the model evaluation results and performance comparison chart.

## Key Findings

The experiments demonstrate how regularization strength affects regression model performance. Excessive regularization may lead to underfitting and lower R² scores.
