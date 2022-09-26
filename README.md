# Bitcoin Time Series Forecasting Using Prophet Algorithm 

In this notebook I'll use Prophet time series forecasting algorithm to attempt to forecast Bitcoin's price for the next thrirty days.

[Prophet](https://facebook.github.io/prophet/) is an open source forecasting package that was developed by Facebook’s data science research team. The procedure for forecasting time series data is based on an univariate additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.


[**Bitcoin** **(BTC)**](https://www.coingecko.com/en/coins/bitcoin) is a scarse decentralized digital currency intoduced into the world in 2009 by a person or group of people using the pseudonym Satoshi Nakamoto. It can be transferred on the peer-to-peer bitcoin network. Bitcoin transactions are verified by network nodes through cryptography and recorded in a public distributed ledger called a blockchain.


As of August 31st 2022
Circulating supply of BTC: 18,925,000

Market Capitalization: $412 Billion USD

Market Cap Rank: #1 (among all cryptocurrencies)

Trading Volume: $27,851,916,129 USD

Current Price: $20,000 USD per unit


You can find two jupyter notebooks in this repository. Both have the exact same content. The only differences are:

BTC_Time Series_Forecast.ipynb : Configured so that the plotly charts render on nbviewer. You can check it out [here](https://nbviewer.org/github/efrenmo/Forecasting_BTC_with_Prophet/blob/77f599770ee2602055edc932d0758dadd00f78cc/BTC_Time%20Series_Forecast.ipynb)
Bitcoin Time Series Forecast.ipynb: Configured so that the plotly charts render on google colaboratory notebook only. 
