## Stock Price Prediction

# Tech Stack: 
Programming Language: Python


Libraries: TensorFlow, Keras, scikit-learn, pandas, numpy, matplotlib

Environment: Jupyter Notebook

# Project Steps
1. Data Collection: Gather historical stock price data.

2. Data Preprocessing:
-Load the data.

-Handle missing values.

-Scale the data using MinMaxScaler.

3. Create Training and Testing Sets:

-Define the time step (window size).

-Split the data into training and testing sets.

4. Build LSTM Model:

-Define the model architecture.

-Compile the model with appropriate loss function and optimizer.

5. Train the Model:

Fit the model on training data.

Use validation split to monitor performance.

6. Evaluate the Model:

Predict on test data.

Inverse transform the predictions and actual values.

Calculate evaluation metrics (MAE, MSE, RMSE, R-squared).

7. Visualize Results:

Plot actual vs. predicted stock prices.

Plot future stock price predictions.

8. Future Predictions:

Generate future dates.

Predict future stock prices.

Plot the predicted future prices


