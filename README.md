# 📈 Apple Stock Price Prediction using RNN

This project builds and trains a Recurrent Neural Network (RNN) using `TensorFlow` and `Keras` to predict Apple (AAPL) stock prices based on historical closing prices from Yahoo Finance.

## 🚀 Features

- Fetches historical stock data from Yahoo Finance using `yfinance`
- Scales data using `MinMaxScaler` for neural network input
- Creates time-series sequences for supervised learning
- Builds and trains a custom RNN model using `SimpleRNNCell`
- Visualizes the closing price and model training performance

## 🧠 Model Architecture

- `RNN` Layer 1: 50 units with ReLU activation, `return_sequences=True`
- `RNN` Layer 2: 50 units with ReLU activation
- `Dense` Layer: 1 unit for next-step price prediction
- Optimizer: Adam
- Loss: Mean Squared Error

## 🛠️ Installation

```bash
pip install pandas numpy matplotlib yfinance scikit-learn tensorflow
