# Airline Passengers Time Series Analysis
Univariate time series analysis of airline passenger data using Python.   
Reference: https://www.kaggle.com/andreazzini/international-airline-passengers   
   
Various methods / models were investigated to forecast 12 months into the future.   
The methods include:   
* Simple moving averages
* Exponentially weighted moving average
* Holt-Winters method
* Facebook Prophet
* ARIMA based models, specifically SARIMA
* Recurrent Neural Network
   
The Triple Exponential Smoothing (Holt-Winters) method performed the best with a root mean squared error of 10.48%.   
The "trend" was set to multiplicative and the "seasonal_periods" was set to 12 (months).
