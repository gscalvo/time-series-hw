# Unit 10 - A Yen for the Future

## Time-Serie Forecasting

* Based on your time series analysis, would you buy the yen now?

Based on the analysis, the yen is not a good buy right now. Both, the ARMA model and the ARIMA model, were not good fits for the data - their P values were far above 0.05

* Is the risk of the yen expected to increase or decrease?

The risk is expected to increase

* Based on the model evaluation, would you feel confident in using these models for trading?

Absolutely not. The GARCH model predicts a high variance in the upcoming dates. This is far above my risk tolerance.

## Linear Regression Forecasting

* Does this model perform better or worse on out-of-sample data compared to in-sample data?

The RMSE for out of sample is 0.41 compared to an in-sample RMSE of 0.71 - this means that the model performed better with out of sample data