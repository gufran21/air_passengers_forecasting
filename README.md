# Flight Passengers Time Series Analysis and Forecasting
## Overview
This repository contains code and resources for analyzing time series data of flight passengers and forecasting the number of passengers for future days. The analysis is primarily based on ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models.

![output](https://github.com/gufran21/air_passengers_forecasting/assets/111707501/30880b0b-fde4-4a51-84d0-64156abb0804)

## Data
The dataset used for analysis consists of historical records of flight passengers. It includes information such as date, number of passengers.

## Models
- **ARIMA** (AutoRegressive Integrated Moving Average): This model is used to capture the temporal dependencies and trends in the data.
- **SARIMA** (Seasonal ARIMA): SARIMA extends ARIMA to handle seasonality in the data. It's particularly useful for capturing recurring patterns over specific time intervals.

## Steps
- **Data Preparation:** Ensure the dataset is preprocessed and formatted appropriately for time series analysis. This may include handling missing values, converting data types, and setting the datetime index.
- **Model Training:** Train the ARIMA and SARIMA models using historical data. Tune the model parameters (e.g., order, seasonal_order) based on performance metrics such as AIC (Akaike Information Criterion).
- **Model Evaluation:** Evaluate the trained models using validation data or cross-validation techniques. Assess their performance metrics (e.g., RMSE, MAE) to gauge forecasting accuracy.
- **Forecasting:* Utilize the trained models to forecast the number of passengers for future days. Visualize the forecasted values along with confidence intervals to convey uncertainty.

## Requirements
Python (version 3.10.4)
Libraries: pandas, numpy, statsmodels, matplotlib, seaborn, etc.
