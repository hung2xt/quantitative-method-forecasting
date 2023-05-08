## quantitative-method-forecasting
1. Using Supervised method to predict a stock price
#### Problem definition: 
In the supervised regression framework used for this case study, the weekly return of Microsoft stock is the predicted variable. We need to understand what affects Microsoft stock price and incorporate as much information into the model. Out of correlated assets, technical indicators, and fundamental analysis, we will focus on correlated assets as features in this case study. For the purpose of personal research, other than the historical data of Microsoft, the independent variables used are the following potentially correlated assets:
  - Stocks: IBM (IBM); Alphabet (GOOGL)
  - Currency: USD/JPY; GBP/USD
  - Indices:S&P 500; Dow Jones; and VIX

The dataset used for this case study is extracted from Yahoo Finance and the FRED website. In addition to predicting the stock price accurately, this case study will also demonstrate the infrastructure and framework for each step of time series and supervised regression–based modeling for stock price prediction. We will use the daily closing price from 2010 to 2022.
