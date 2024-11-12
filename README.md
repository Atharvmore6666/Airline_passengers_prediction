# Airline_passengers_prediction
This project uses SARIMA modeling to forecast monthly airline passenger numbers. Key steps include data preprocessing, seasonal decomposition, model selection with Auto ARIMA, and evaluation of forecasted values against historical data.

## Dataset Information
The dataset contains the following columns:
- **Month** (`datetime64`): The month and year of observation, used as the time index.
- **Passengers** (`int64`): The number of airline passengers recorded each month.


## Motivation
Accurate passenger forecasting is crucial for the aviation industry to optimize resource allocation, manage capacity, and improve customer satisfaction. By using SARIMA, this project aims to capture underlying patterns in airline passenger data to enable informed decision-making.

## Steps
1. Data preprocessing, including parsing dates and setting the index.
2. Log transformation to stabilize variance.
3. Seasonal decomposition to identify trends, seasonality, and residuals.
4. SARIMA model fitting and parameter selection using Auto ARIMA.
5. Forecasting and comparing predictions with actual data.

## Conclusion
The SARIMA model captured seasonal patterns and provided reliable forecasts, confirming its potential for airline passenger demand forecasting. This project exemplifies time series forecasting's application in operational planning and capacity management.

## Requirements
- pandas
- matplotlib
- numpy
- statsmodels
- pmdarima
