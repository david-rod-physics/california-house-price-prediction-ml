# California House Price Prediction with Machine Learning

## Overview

This project explores the California Housing dataset using several machine learning regression models. The objective is to compare model performance, analyse prediction errors, investigate overfitting, and identify the most important features influencing house prices.

## Dataset

- California Housing Dataset (scikit-learn)
- 20,640 census block groups
- 8 numerical features
- Target: Median house value (in units of $100,000)

## Models Compared

- Linear Regression
- Decision Tree Regression
- Random Forest Regression

## Evaluation Metrics

- Mean Absolute Error (MAE)
- R² Score

## Key Results

| Model | MAE | R² |
|-------|-----:|----:|
| Linear Regression | 0.53 | 0.576 |
| Decision Tree (Depth 10) | 0.433 | 0.683 |
| Random Forest | **0.328** | **0.805** |

The Random Forest achieved the best overall performance while still showing moderate overfitting compared with its training performance.

## Skills Demonstrated

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Linear Regression
- Decision Trees
- Random Forests
- Model Evaluation
- Residual Analysis
- Feature Importance Analysis

## Future Improvements

- Hyperparameter tuning using cross-validation
- Explore additional regression algorithms
- Evaluate on more recent housing datasets
