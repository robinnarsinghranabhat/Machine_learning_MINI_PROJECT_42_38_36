# Machine_learning_MINI_PROJECT_42_38_36
As per the mini project for machine learning
## We used a 3M stock price value varying day by day to train a RNN model.

since the RNN model are naturally on the go Model for Time series data, we used RNN with GRU cell.
GRU cell is extensively found to be simpler than LSTM (less no. of gates / parameters) and also, prevents vanishing gradient problem.


## DATASET SOURCE

ALL STOCK PRICE DATASET : https://github.com/not4win/MLfinance/blob/master/all_stocks_5yr.csv

From this dataset, we take out stock price for 3M company and train the model.
