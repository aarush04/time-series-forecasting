# Time Series Forecasting with ARIMA and SARIMA

## Overview
This project explores time series forecasting techniques using a dataset of monthly international airline passenger counts from 1949 to 1960. The goal was to build predictive models to understand historical trends and forecast future passenger numbers. The analysis involved making the data stationary, identifying model parameters, and implementing ARIMA and SARIMA models for trend prediction.

## Dataset
The dataset consists of:
- Monthly records of international airline passenger numbers.
- Timeframe: 1949–1960.

## Key Steps
1. **Data Visualization**:
   - Plotted the time series data to identify overall trends and seasonal patterns using Matplotlib.
   
2. **Stationarity Check**:
   - Applied differencing techniques to remove trends and seasonality, making the data stationary.
   - Performed the Augmented Dickey-Fuller test to confirm stationarity.

3. **Model Parameter Identification**:
   - Constructed Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to determine AR and MA values for the ARIMA model.

4. **Model Building**:
   - Implemented the ARIMA model for initial non-seasonal trend forecasting.
   - Extended to the SARIMA model to account for seasonal components in the data.

5. **Forecasting**:
   - Predicted future passenger counts and compared model results to actual trends for validation.

## Tools and Technologies
- **Python**: Primary programming language.
- **Pandas & NumPy**: For data preprocessing and statistical calculations.
- **Matplotlib**: For data visualization.
- **Statsmodels**: To implement ARIMA and SARIMA models.

## Results
- Successfully modeled the historical trends and forecasted passenger counts for future months.
- Provided insights into seasonal patterns and long-term trends.

## Acknowledgment
This project was completed under the guidance of **Amit Kundaliya** and **Aditee Gupta**.
