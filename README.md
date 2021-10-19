# yen_for_the_future
Test the Time Series Tools to predict future movements in the value of the Japanese Yen versus the US Dollar.

# Time-Series Forecasting
## Return Forecasting: Initial Time-Series Plotting

Do you see any patterns, long-term and/or short?
**Answer:** Long-term trend is up on the Yen, the fluctuations on the Yen seem quite large with 9000 being a significant pivot point.
 Short-term trend from around 2016 is up with a symmetrical triangle pattern in formation.

## Forecasting Returns using an ARMA Model

Based on the p-values, is the model a good fit (p < 0.05)?
**Answer:**     
   1. Based on the output of the ARMA summary table the p-values of the lags are greater than 0.05 thus not being considered a good fit.

## Forecasting the Settle Price using an ARIMA Model

Based on the p-values, is the model a good fit (p < 0.05)?
   * Based on the output of the ARIMA summary table the p-values of the lags are greater than 0.05 thus not being considered a good fit.
   
What does the model forecast will happen to the Japanese Yen in the near term?
   * Based on the 5 day forecast for the Settle Price the model forecasts that the Japanese Yen will rise in the near term.

## Volatility Forecasting with GARCH
### Conclusion

1. Based on your time series analysis, would you buy the yen now?
    * Based on the analysis undertaken it shows that the Japanese Yen is likely to increase in value, thus would potentially be a good time to buy.
2. Is the risk of the yen expected to increase or decrease?
    * The volatility of the Japanese Yen is expected to increase in the short-term view.
3. Based on the model evaluation, would you feel confident in using these models for trading?
    * Based on the models I would not be overly confident in using these as the model is not a good fit due to the fact that the p > 0.05.  Ideally this should be p < 0.05.


# Linear Regression Forecasting

## Conclusions

Does this model perform better or worse on out-of-sample data compared to in-sample data?
* The results from the Linear Regression analysis and modeling reveal the following:
    1. Out-of-Sample RMSE of 0.415 was lower than the In-sample RMSE of 0.596.
    2. The In-Sample result should generally be lower than the Out-of_Sample data.
    3. In this case the model performed worse on out-of-sample data!
    