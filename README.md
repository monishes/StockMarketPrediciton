# StockMarketPrediciton
This is a Machine Learning Model that predicts the stock price of Tata Power using the Long Short Term Memory Recurrent Neural Network

This project uses the previous data of stock prices of Tata Power over a period of 1.5 years. I used LSTM neural network model to predict the final Closing price of the stock in the near future.

The Independant variables are the data of the previous years :
                1) Market Opening Price
                2) Market High Price
                3) Market Low Price
                4) Market Last Price
 
I used 4 LSTM (Long Short Term Memory) layers with 50 units/neurons in each layer and a dropout with a value of 0.2 at each layer. We then trained this neural network for the training set for over 500 epochs.
The Predicted Stock Prices were so close to that of the actual values, and the values shadow the pattern of that of the original values exactly, with a very slight deviation in values.
The Graph is Shown below :

![download](https://user-images.githubusercontent.com/57072184/184416065-181fde23-f16b-41cf-9af0-80d1111b3f24.png)
