Stock Price Prediction Model

This project uses a Linear Regression model to predict stock prices based on historical data. The model incorporates technical indicators such as Simple Moving Average (SMA) and Relative Strength Index (RSI) to predict the stock's next day's closing price.
Project Overview

In this project, I build a stock price prediction model using Linear Regression. 
The goal of the model is to predict the next day’s stock price based on key technical indicators such as:

50-day Simple Moving Average (SMA_50)
200-day Simple Moving Average (SMA_200)
Relative Strength Index (RSI)
Volume

The model is trained on historical stock data and uses the current stokc trends to predict the next day's closing price.

Requirements

To run this project, you will need the following libraries:

Python 3
pandas: For data manipulation.
numpy: For numerical operations.
matplotlib: For data visualization.
scikit-learn: For building the Linear Regression model.
ta: For calculating technical analysis indicators like RSI, SMA.

Model Description

This model uses Linear Regression to predict the stock price. It considers the following features:

SMA_50: The 50-day Simple Moving Average.
SMA_200: The 200-day Simple Moving Average.
RSI: The Relative Strength Index, a momentum indicator.
Volume: Trading volume for the stock.

How the Model Works:
Training: The model is trained on historical stock data using SMA_50, SMA_200, RSI, and Volume as input features.
Prediction: The model predicts the stock's next day's closing price based on the current day's data.
Results

The model outputs a prediction for the next day's closing price based on the most recent data.

The accuracy of the model can be evaluated using the metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE).
