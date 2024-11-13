# Error Correction Model (ECM) in Python

## Training a standard 2-step ECM involves the following steps:
1. Stationary and Cointegration Tests: y and X are non-stationary, but they need to be cointegrated!
2. Long run regression, long-run residuals are stationary (passes the cointegration tests)
3. Short run regression

## To make forecast, you have the following steps:
1. Use long run regression to create an "equilibrium" forecast
2. Start from launch point, use the short run regression to correct the errors

