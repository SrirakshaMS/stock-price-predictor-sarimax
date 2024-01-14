# Stock Price Prediction using SARIMAX Forecasting
SARIMAX forecasting on time-series data and implementing strategic feature engineering to predict stock's close prices

1. ### Data Preprocessing and Exploration:
   - Utilized Augmented Dickey-Fuller Test to confirm non-stationarity, then applied differencing for stationarity.
   - Conducted seasonal decomposition, revealing clear seasonal patterns in the data.
   - Employed ACF and PACF plots to determine SARIMA model parameters.

2. ### Modeling and Validation:
   - Developed SARIMAX model with order (1, 0, 1) for predicting 'Close' prices.
   - Implemented feature engineering, splitting the dataset into training and validation sets (80:20 ratio).
   - Achieved a high accuracy of 95.61% on the validation set using SMAPE evaluation.

3. ### Testing on Unseen Data:
   - Applied the trained SARIMAX model to test data, incorporating the same feature engineering steps.
   - Generated accurate forecasts for 'Close' prices on the test dataset.
   - Visualized the forecasted 'Close' values, demonstrating close alignment with 'Open' prices.

5. ### Visualization:
   - Plotted the forecasted 'Close' values against the 'Open' prices, showcasing the accuracy of predictions.
   - Provided a statistical summary of the submission DataFrame for further analysis.
