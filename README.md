# Custom Loss Function for Time Series Forecasting

## Overview
This project introduces a custom loss function that combines Mean Squared Error (MSE) with a smoothness penalty to improve time-series predictions.

## Motivation
Standard loss functions like MSE do not enforce smooth predictions, which is critical in time-series tasks like stock prices and weather forecasting.

## Method
Custom Loss = λ₁(MSE) + λ₂(Smoothness Penalty)

- MSE ensures prediction accuracy
- Smoothness penalty reduces abrupt changes

## Datasets
- Jena Climate Dataset
- S&P 500 Dataset
- Google Finance Dataset

## Results
- Achieved R² score up to **0.9967**
- Outperformed MSE, MAE, and Huber Loss

## Tech Stack
- Python
- NumPy
- Machine Learning

## How to Run
```bash
