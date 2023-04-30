# Bank Stock Price Forecasting & Time Series Analysis

## Part I - EDA

Time series analysis of megabank stock, including BAC, JPM, HSBC, RY... in the past 20 years, from 2003 till 2023.

### Price change over the past 20 years

![1](asset/stock_price.png)

### 2023 Q1 daily return
It shows 2023 March banking crisis including the collapse of SVB significantly impacted the price drop for major banks.

![2](asset/stock_return.png)

### Comparison of yearly return among megabanks
For the past 20 years, JPM generates a relative higher and more stable yoy return, outperforming other mega banks. While RBC & PD, as well as MS and GS indicates similar return and risk patterns.  

![4](asset/comp_yr.png)


## Part II - LSTM for Time Series Forecasting

Forecast short-term JPM stock price based on the past 60-day close price.

![3](asset/LSTMforecasting.png)
