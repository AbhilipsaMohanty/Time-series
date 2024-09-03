# Time-series
### Objective
The main objective of this project is to leverage ARIMA and Exponential Smoothing techniques to forecast future exchange rates based on historical data provided in the exchange_rate.csv dataset. The analysis aims to identify the most suitable model for accurate exchange rate predictions.

### Dataset
The dataset contains historical exchange rates, with each column representing a different currency rate over time. The primary focus is on the exchange rates from USD to Australian Dollar, with the first column indicating the date.

### Part 1: Data Preparation and Exploration
Data Loading
2. Data Import: Load the exchange_rate.csv dataset and appropriately parse the date column to ensure accurate time series analysis.
3. Initial Exploration
Time Series Plotting: Plot the time series for the currency to identify trends, seasonality, and any anomalies present in the data.
4. Data Preprocessing
Handling Missing Values: Address any missing values or anomalies identified during the exploration phase to ensure clean and reliable data for modeling.
### Part 2: Model Building - ARIMA
1. Parameter Selection for ARIMA
ACF and PACF Analysis: Utilize ACF and PACF plots to estimate initial parameters (p, d, q) for the ARIMA model.
2. Model Fitting
ARIMA Implementation: Fit the ARIMA model with the selected parameters to the preprocessed time series data.
3. Diagnostics
Residual Analysis: Analyze the residuals to ensure there are no patterns, indicating that the model is adequate and well-fitted.
4. Forecasting
Out-of-Sample Forecasting: Perform out-of-sample forecasting and visualize the predicted values against the actual values to assess model performance.
### Part 3: Model Building - Exponential Smoothing
1. Model Selection
Model Choice: Based on the time series characteristics, choose an appropriate Exponential Smoothing model (e.g., Simple, Holt’s Linear, or Holt-Winters).
2. Parameter Optimization
Optimization Techniques: Utilize techniques such as grid search or AIC to find the optimal parameters for the smoothing levels and components.
3. Model Fitting and Forecasting
Exponential Smoothing Implementation: Fit the chosen Exponential Smoothing model and forecast future values. Visually compare these forecasts with the actual data to evaluate accuracy.
### Part 4: Evaluation and Comparison
Compute Error Metrics
1. Evaluation Metrics: Use metrics such as MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), and MAPE (Mean Absolute Percentage Error) to evaluate and compare the forecasts from both models.
Model Comparison
2. Performance Discussion: Discuss the performance, advantages, and limitations of each model based on the observed results and error metrics.
### Conclusion
Summary of Findings: Summarize the findings, highlighting which model(s) yielded the best performance for forecasting exchange rates in this dataset. Provide insights and recommendations based on the analysis conducted.
