## Stock Market Prediction With LSTM
#### Project Overview

This project explores the application of Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), for stock market price prediction using PyTorch. LSTMs are well-suited for time series forecasting tasks due to their ability to capture long-term dependencies within sequential data.

#### Data Acquisition and Preprocessing

Data Source:  Yahoo Finance
Features: The initial data contained the closing price, opening price, volume, low and high prices but we made use of just the close priceand took a lag of 7 days for our features.
