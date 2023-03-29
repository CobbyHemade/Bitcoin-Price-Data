# Bitcoin-Price-Forecast-Using-LSTM-Machine-Learning-Model-
In this code, we first import the necessary libraries such as pandas, numpy, scikit-learn's MinMaxScaler, Keras' Sequential and Dense classes,
and Keras' LSTM layer. Then, we load the Bitcoin price data from a CSV file uploaded on this repository. We normalize the target variable and 
split the data into training and testing sets.

Next, we prepare the input features and target variable for both sets and reshape the input data to fit the LSTM model. We build a two-layer
LSTM model with 50 units in each layer and compile it with the mean squared error loss and Adam optimizer. We train the model using the training
set and validate it using the testing set.

After training, we make predictions on the testing set and inverse transform the normalized predictions to the original scale. We plot the actual 
and predicted Bitcoin prices using Matplotlib. Finally, we make a prediction for a future price by passing in a new set of feature values and 
inverse transform the normalized prediction to the original scale.

Here is a link to the google colab file
https://colab.research.google.com/drive/1YdTJdRxfS37MQgLRddKi1y80d9FeF5Gz#scrollTo=VFPGtTzM2P48
