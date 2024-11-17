# Error Correction Model (ECM) in Python

## Training a standard 2-step ECM involves the following steps:
1. Stationary and Cointegration Tests: y and X are non-stationary, but they need to be cointegrated!
2. Long run regression, long-run residuals are stationary to be an input for short run regression
3. Short run regression: short-run variables need to be stationary.

## To make forecast, you have the following steps:
1. Use long run regression to create an "equilibrium" forecast
2. Start from launch point, use the short run regression to correct the errors

