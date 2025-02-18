# Stock Price Prediction using LSTM

This project uses a Long Short-Term Memory (LSTM) network to predict the closing stock price of Apple Inc. (AAPL) based on historical stock data. The model uses a time-series analysis technique to train on the past 60 days' closing stock prices and predicts future stock prices.

## Project Overview

The model is built using the Keras library and trained on data from Yahoo Finance. The LSTM network is particularly well-suited for time-series forecasting due to its ability to remember long-term dependencies in sequential data.

### Key Features:
- **Data Source:** Stock data for Apple Inc. (AAPL) fetched using Yahoo Finance API.
- **Model:** LSTM-based neural network for time-series forecasting.
- **Preprocessing:** Data normalization using MinMaxScaler.
- **Prediction Output:** The model predicts the closing stock price for the next day.
  
## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/stock-price-prediction-lstm.git
cd stock-price-prediction-lstm

