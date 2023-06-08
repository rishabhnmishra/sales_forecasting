# sales_forecasting
Sales forecasting using multiple models - Seasonal Naïve, Holt-Winters, ARIMA, SARIMA and Linear Regression Model

## Project Objective
Goal: The goal of this project was to apply various quantitative methods, (i.e. Times Series Models and Causal Models) to forecast the sales of the products available in the dataset.

- Perform time series analysis to understand the data and trends
- Use multiple forecasting models on train dataset
- Finally select the best model to run the test data

Models covered in the notebook include:
1. Seasonal Naive Model
2. Holt-Winters Model (Triple Exponential Smoothing)
3. ARIMA Model and Seasonal ARIMA Models
4. Linear Regression Model

## Conclusion
We considered different time-series models as well as a regression model for time series forecasting. From our results we saw that the linear regression model outperformed the other time-series models. Therefore, for this dataset we could use a regression model, rather than a time-series model to forecast sales. One of the main assumptions of regression models is that the patterns in the historical data will be repeated in the future, and since our data was highly seasonal and had a linear trend, it made sense why the linear regression model out-performed the other models.
