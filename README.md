# Netflix-Subscriptions-Forecasting
This project provides a Python implementation for forecasting Netflix quarterly subscriptions using time series analysis with ARIMA (AutoRegressive Integrated Moving Average). It includes data visualization with Plotly, quarterly and yearly growth rate analysis, and predictions for future subscription counts.
This repository contains Python code for forecasting Netflix quarterly subscriptions using time series analysis with ARIMA (AutoRegressive Integrated Moving Average) and visualization with Plotly.

**<h5>Prerequisites</h5>**
Make sure you have the necessary Python libraries installed. 
You can install them using the following command:pip install pandas numpy matplotlib plotly statsmodels

**<h5>Data Loading and Exploration:</h5>**
Load Netflix subscriptions data from Netflix-Subscriptions.csv.
Explore the data and visualize quarterly subscriptions growth.

**<h5>Quarterly Growth Rate Visualization:</h5>**
Calculate and visualize the quarterly growth rate of Netflix subscriptions using a bar graph.
Color bars green for positive growth and red for negative growth.

**<h5>Yearly Growth Rate Visualization:</h5>**
Calculate and visualize the yearly growth rate of Netflix subscriptions using a bar graph.
Color bars green for positive growth and red for negative growth.

**<h5>Time Series Analysis with ARIMA:</h5>**
Use ARIMA to analyze the time series data.
Plot autocorrelation function (ACF) and partial autocorrelation function (PACF) to determine model parameters.

**<h5>ARIMA Model Fitting and Prediction:</h5>**
Fit an ARIMA model with determined parameters.
Generate predictions for future steps (default: 5 steps) and visualize the results alongside the original data.

**<h5>Contributing:</h5>**
Contributions are welcome! Feel free to open issues or submit pull requests.
