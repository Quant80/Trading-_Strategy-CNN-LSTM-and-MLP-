# Trading-_Strategy-CNN-LSTM-and-MLP-

Note: The time series used was approx MSFT 2,000 observations.

Step 1:
a. Gathered information on the MSFT time series prices

b. Built a predictive model to forecast the returns.Ensured that the model's labels show some information leakage between training and test samples.

c. Used three deep learning (DL) models to predict the time series, employing a single train/test split. The three models used were:
Multilayer Perceptron (MLP)
Long Short-Term Memory (LSTM)
Convolutional Neural Network (CNN) based on GAF (Gramian Angular Field).

d. Provided information on the results obtained from backtests of the trading strategies derived from each of the three models.

Step 2:
a. Backtested the models using a non-anchored walk forward method with a train/test split of 500 observations in each set.

b. Backtested the models using a non-anchored walk forward method with a train/test split of 500 observations in the training sets and 100 observations in the test sets.

c. Discussed the changes in the backtest results from parts a and b compared to Step 1.

d. Compared the backtest results between parts a and b and discussed whether backtest overfitting due to leakage can explain the observed results.

Step 3:
a. Set up and described a method to reduce the extent of leakage between training and test samples to alleviate information leakage.

b. Used the leakage reduction method to train the models using a non-anchored walk forward method with a train/test split of 500 observations in each set.

c. Used the leakage reduction method to train the models using a non-anchored walk forward method with a train/test split of 500 observations in the training sets and 100 observations in the test sets.

d. Discussed how the results of the backtests in parts b and c compare. Examined whether overfitting appears to have disappeared compared to Step 2.
