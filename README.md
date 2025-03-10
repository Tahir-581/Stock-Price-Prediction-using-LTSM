# Stock Price Prediction Using LSTM

This project implements an LSTM (Long Short-Term Memory) neural network to predict stock prices using historical data from Yahoo Finance. The model is trained on Apple's (`AAPL`) stock price data from 2010 to 2023.

## Features
- Fetches historical stock price data using `yfinance`
- Preprocesses data using MinMax scaling
- Creates sequential input data for LSTM
- Trains an LSTM-based deep learning model
- Evaluates performance using Mean Absolute Error (MAE) and R-squared (R²) score
- Visualizes actual vs. predicted stock prices

## Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install numpy pandas yfinance scikit-learn tensorflow matplotlib
