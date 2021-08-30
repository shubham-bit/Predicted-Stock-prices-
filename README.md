# Predicted-Stock-prices 

Imported the data from yahoo finance and used TESLA stock data for the model.
Creating the data frame for close price. We will only use Close price for this model.
Scaling the data. We will be using MinMaxScaler. MinMaxScaler is used when we need to rescale the dataset such that the features values are in the range [0,1]
Reshaping the training data which can be used in the LSTM Model.
Compile the Model.
Preparing the test data, feature scaling and reshaping.
Predicting the output from from the test data.
Scaling the data back to the original format.
Comparing our model's prediction with the actual closing price..
