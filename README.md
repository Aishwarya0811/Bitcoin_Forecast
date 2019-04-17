# Bitcoin_Forecast

Prediction (forecasting)

## Measures of Forecast Accuracy 

. MSE: the Mean Squared Error between forecast and actual  

. MAD: the Mean Absolute Deviation between forecast and actual

. MAPE: the Mean Absolute Percent Error between forecast and actual

## Autocorrelation (Serial Correlation)
Yt  =  b’xt  +  εt
Cov(εt, εt-1) ≠ 0

## Distributed lag model

## Stationary Time Series

1. Go online and search for daily bitcoin prices. Find and download a historical series of bitcoin prices going back to at least 2014.

2. Go to St Louis FRED. Find and download the S&P500 (SP500), the London bullion market price for gold in US dollars (GOLDAMGBD228NLBM), the US/Euro exchange rate (DEXUSEU), and the West Texas Intermediate spot price of oil (DCOILWTICO). These should all be available daily as well.

3. Merge all the data sets together.

4. Plot the series.

5. Use a regression to Önd spurious correlations to the bitcoin price in the data set (e.g., regress the bitcoin price on the other series without any di§erencing to see if you Önd any interesting but total bullshit relationships).

6. Use the KPSS test to Önd how many di§erences each series takes to become stationary.

7. After taking di§erences, regress the bitcoin price on the other series. What relationships do you Önd now?

8. Remove all the data before 2017 where the bitcoin price starts to spike. Plot the new data. This is the data you are to use for the rest of the question.
1
9. Plot the ACF and PACF of the bitcoin price

10. Fit various arima models to the bitcoin price. Which model Öts best using the AIC?

11. Forecast the next 30 days of the bitcoin price and plot the forecast.

12. Plot the periodogram of the data. Do you see any seasonality in the data?

13. Using the AIC, select a VAR model which best captures the relationships between our 5 variables. 14. Forecast the next 30 days of the prices using the VAR model.
