# Stock Price Prediction using LSTM

This project aims to predict stock prices using Long Short-Term Memory (LSTM) neural networks. The LSTM model is trained on historical stock price data fetched from Yahoo Finance and then used to predict future stock prices.

## Overview

The code provided demonstrates the following steps:
- Fetching historical stock prices using `yfinance`
- Preprocessing the data by normalizing it with `MinMaxScaler`
- Building an LSTM model using TensorFlow/Keras
- Training the LSTM model
- Making predictions and evaluating the model's performance

## Prerequisites

To run this code, you'll need:
- Python 3
- Required libraries: `yfinance`, `numpy`, `pandas`, `scikit-learn`, `tensorflow`, `matplotlib`

## Usage

1. Clone this repository.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the provided code in a Python environment.
4. The code trains an LSTM model on historical stock data and plots the actual vs. predicted stock prices.

## Code Explanation

The main components of the code include:
- Importing necessary libraries
- Fetching historical stock data
- Data preprocessing (normalization)
- Splitting the data into training and testing sets
- Building and training the LSTM model
- Making predictions and evaluating the model's performance

## Results

The code outputs the Root Mean Squared Error (RMSE) as a measure of the model's performance. Additionally, it generates a plot illustrating the actual vs. predicted stock prices.

![Stock Price Prediction](path/to/stock_prediction_plot.png)

## Disclaimer

This code serves as a basic demonstration and may require further refinement for production-level use. Stock market prediction is inherently uncertain, and this model's predictions should be interpreted with caution.

