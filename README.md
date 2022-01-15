In this project, we aim to predict the bitcoin price. In this regard, we use the BTC-USD dataset provided by Yahoo!. 
Since bitcoin's price depends on the previous prices, we must use recurrent networks. 
Here we use RNN, LSTM, GRU networks. 
In the training part, the chosen time series contains 24 consecutive prices. We aim to predict Bitcoin price in the next week in the testing part. 

In order to find the best data transformation method, we apply 3 different data transformations on our dataset.
