# Yen Future Valuation
![Yen Photo](Images/readme_photo.png)

## Goal  
Use ARMA, ARIMA, and GARCH models from time-series first, and then regression analysis to predict future movements in the value of Japanese Yen futures

## Objective
Leverage insights to make theoretical investment decisions. 

-------------------------------------------------------------

# Yen Future Analysis using Time Series

### Based time series analysis, should we buy the yen now? 

The ARIMA model results forecast an increase in Yen future settle price over the next 5 days, and the ARMA model suggests the same for Yen future returns.   

### Is the risk of the yen expected to increase or decrease?

It should be noted that the 5 day volatility forecast from our GARCH model suggests a daily increase in Yen future volatility. As a result, we should expect Yen future risk to increase.   

### Based on the model evaluation, would you feel confident in using these models for trading?

P-values are both significantly greater than .05 for ARMA and ARIMA. Therefore, I would NOT feel confident using these instances of ARMA or ARIMA to trade. However, we may be confident in our volatilty forecast since GARCH model p-val is 3.707e-02 (nearly .003).