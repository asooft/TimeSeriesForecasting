# Time Series Forecasting
• Pick an evaluation metric such as RMSE for overall model comparisons.

• We evaluate model using roll-forward approach, simple train-test split and time series sklearn cross validation.

• We analyze time series data using visual plots and comment on your visual.

• Start forecasting using the below approaches, with each commenting on why results is produced like that, pros and cons:
1. Simple Moving Average.
2. Naïve Forecasting.
3. Weight Moving average using any weights you find make sense based on your data understanding.
4. Simple Linear Regression Model.
5. Forecast using classical decomposition approach, and comment on decomposed components.
6. Forecast using STL decomposition approach. Compare decomposed components between this approach & classical.
7. ARIMA/S-ARIMA model. Apply different ARIMA models based on what you see from ACF, PACF plots and summary
statistics and residuals analysis and using also AIC or BIC. Don’t forgot to check stationarity first and transform it if
needed.
8. Exponential Smoothing. Apply single, double and triple exponential smoothing approach and comment on results and
whether dampening is needed or not theoretically and practically.
9. Apply Facebook Prophet Algorithm.
10. Apply supervised ML algorithm such as XGBOOST Regressor. Use features which are lags (𝑌𝑡−1, 𝑌𝑡−2, … , 𝑎𝑣𝑔(𝑦𝑡−𝑛))

• We comment and justify why each approach succeeds or fails based on our understanding.
