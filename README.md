# Overall Look at Stock_Prediction_Microsoft

In this project I was able to use Machine Learning to predict price of stocks using a machine learning technique called Long Short-Term Memory (LSTM). Although the stock price can be affected by many different things, I was able to get some results that are slightly better than guessing.

# Long short-term memory (LSTM) 

LSTM is an artificial recurrent neural network (RNN) architecture used in the field of deep learning and are widely used for sequence prediction problems and have proven to be extremely effective. "Unlike standard feedforward neural networks, LSTM has feedback connections. It can not only process single data points (such as images), but also entire sequences of data (such as speech or video)". 
--Wikipedia--
The reason they work so well is because LSTM is able to store past information that is important, and forget the information that is not.

# Compiling the Model

optimizer = adam and the optimizer is used to improve upon the loss
loss function = mean_squared_error (MSE) and loss functions are used to measure how well the model did on training

# Results of the project
The LSTM Model was able to predict the Microsoft stock to be 149.5 $ on Decemeber 10th based on the previous 60 days of the market activity whereas the real price was 151 $.
