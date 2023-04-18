# Stock Data Forecasting with LSTM and Hyperparameter Tuning
This repository contains a Long Short-Term Memory (LSTM) forecasting model for predicting stock prices, along with hyperparameter tuning. The model is trained on historical stock data collected from the yfinance Python library.

Note - both of the folders contain the same program, one is a notebook, the other a raw python script using OOP

## Dataset
The dataset used for training and testing the LSTM forecasting model is collected from the yfinance library, which provides access to historical stock data from various financial markets.

## Model Overview
The LSTM forecasting model is designed to predict future stock prices based on historical stock data. LSTM is a type of recurrent neural network (RNN) that is well-suited for sequential data, such as time series data, due to its ability to capture long-term dependencies. The model is trained on historical stock data, and hyperparameter tuning is performed to optimize the model's performance.

## Usage
To use this LSTM forecasting model for stock data, follow the steps below:

- Data Collection: Collect historical stock data from yfinance or any other reliable source, and prepare it for training the LSTM model. Make sure the data includes the required features for training the model, such as stock prices and trading volumes.

- Model Training: Train the LSTM model using the prepared stock data. Hyperparameter tuning techniques, such as grid search or random search, can be applied to optimize the model's hyperparameters for better performance.

- Model Evaluation: Evaluate the trained LSTM model using appropriate metrics

- Prediction: Once the LSTM model is trained and evaluated, you can use it to make stock price predictions for future time steps based on new, unseen data.