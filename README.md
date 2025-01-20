# LSTM-Based Stock Price Prediction Model

## Overview

This project implements a Long Short-Term Memory (LSTM) model for stock price prediction using historical data. The goal is to leverage the temporal dependencies in sequential data to forecast stock prices for algorithmic trading.

The model is designed to predict the stock's closing price based on historical price trends, offering a practical approach to time-series forecasting in the financial domain.

---

## Features

- **Data Preprocessing**:
  - Handles missing values and normalizes data.
  - Converts raw stock data into sequences for LSTM training.
- **Model Architecture**:
  - Sequential LSTM model for capturing long-term dependencies.
  - Dense output layer for predicting stock prices.
- **Training and Testing**:
  - Uses 80% of data for training and 20% for testing.
  - Validation loss monitoring to prevent overfitting.
- **Evaluation Metrics**:
  - Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
  - Visual comparisons of actual vs. predicted prices.
- **Visualization**:
  - Loss curves to analyze model training performance.
  - Graphs showing predicted and actual stock prices.

---

## Dataset

- **Source**: Yahoo stock price data from Kaggle.
- **Data Range**: 2015–2020.
- **Key Features**: Date, Open, High, Low, Close, and Volume.
- **Preprocessing**:
  - Normalization using Min-Max Scaling.
  - Sequence creation with 50-day lookback windows.

---

## Tools and Technologies

- **Programming Languages**: Python
- **Libraries**:
  - `pandas` and `NumPy` for data manipulation.
  - `scikit-learn` for normalization and evaluation metrics.
  - `TensorFlow` and `Keras` for model building and training.
  - `matplotlib` for data visualization.
