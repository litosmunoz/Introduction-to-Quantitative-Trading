# Final Project - Introduction to Algorithmic Trading 

## Introduction: 
The idea behind this project is to:
- Analyze the current US economy, exploring data from TradingView. 
- Make predictions of the U.S. stock market (S&P 500 and NASDAQ 100), Gold and Bitcoin, fitting the Prophet() model.
- Back test and create a profitable trading strategy.
- Implement the Trading Strategy, deploying a crypto trading bot, connected to Bybit's API.


## Variables: 
The variables used to analyze market conditions are split in four cycles: 
- **Credit Cycle**: 
    - 10Y Bond minus 2Y Bond Spread
    - Interest Rates
    - Dollar index (DXY)
    - Volatility index (VIX)

- **Growth Cycle**: 
    - Gross Domestic Product (GDP) Change YoY
    - Manufacturing Purchasing Managers Index (PMI)
    - Unemployment Rate

- **Inflation Cycle**:
    - Consumer Price Index (CPI) Change YoY

- **Liquidity Cycle**: 
    - Monetary Supply (M2)


## Assets:
The assets that I wanted to predict its future price were:
- Bitcoin
- SP 500
- NASDAQ 100
- Gold

## Prediction Model:
To predict stock prices I used the Prophet() model developed by the Data Science Team of Facebook.

## Back testing trading strategies: 
To compare and make sure a strategy is profitable you need to compare different timeframes in different market conditions. In this study I explored Bitcoin's price and tried different buying and selling conditions. I tried using the 15m timeframe, the 1h timeframe and the 4h timeframe, but I finally decided that the most profitable one would be the one implemented to the trading bot. 

## Trading Bot:
I connected to my Bybit's account via an API token and managed to implement the strategy tested with a small change, limiting risks to 2% per trade max.

### Author: 
Carlos Muñoz Fresco