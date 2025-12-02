# Day-Ahead Electricity Price Prediction

Testing different machine learning models to predict the day-ahead electricity price in Germany.

### Inputs

Forecasted Solar, Forecasted Wind Onshore, Forecasted Wind Offshore, Yesterday’s Gas Prices, Forecasted Load, 24-hour lag of Forecasted Load, CO₂ Certificate Prices, 24-hour lagged Day-ahead Price, One-week lagged Day-ahead Price

### Target Variable

Day-ahead Price

## Key Features

### Excel:

Data cleaning

Sin/cos encoding

Adding variable lags

### PowerPoint:

Trend visualisation

Variable dependency overview

### Python:

Model training and evaluation (MSE)

Hyperparameter tuning

Dependency modelling for probabilistic forecasting and stress testing

## Main Focus
### Probabilistic Forecasting

Use the best-performing model with day-ahead input forecasts as mean estimates. Model residual uncertainty using an error copula to generate coherent scenarios, producing a point forecast and confidence intervals.

### Stress Testing

Manual Stress Test:
Set extreme values for selected variables independent of historical dependencies.

Joint Tail Stress:
Sample the copula freely and identify input combinations linked to the predictive tail of the model.

Conditional Stress:
Fix one variable at an extreme level and sample all remaining variables conditionally through the copula.

Tail-of-Tail Conditional Stress:
Fix one variable at an extreme level, sample only from the copula tail for the others, and select the predictive tail of the resulting scenarios.
