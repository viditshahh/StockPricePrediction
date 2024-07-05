## Stock Price Prediction

# Tech Stack: 
Programming Language: Python
Libraries: TensorFlow, Keras, scikit-learn, pandas, numpy, matplotlib
Environment: Jupyter Notebook
# Project Steps
Data Collection: Gather historical stock price data.
Data Preprocessing:
Load the data.
Handle missing values.
Scale the data using MinMaxScaler.
Create Training and Testing Sets:
Define the time step (window size).
Split the data into training and testing sets.
Build LSTM Model:
Define the model architecture.
Compile the model with appropriate loss function and optimizer.
Train the Model:
Fit the model on training data.
Use validation split to monitor performance.
Evaluate the Model:
Predict on test data.
Inverse transform the predictions and actual values.
Calculate evaluation metrics (MAE, MSE, RMSE, R-squared).
Visualize Results:
Plot actual vs. predicted stock prices.
Plot future stock price predictions.
Future Predictions:
Generate future dates.
Predict future stock prices.
Plot the predicted future prices
