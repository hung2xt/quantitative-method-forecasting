## quantitative-method-forecasting
1. Using Supervised method to predict a stock price
### Problem definition: 
In the supervised regression framework used for this case study, the weekly return of
Microsoft stock is the predicted variable. We need to understand what affects Micro‐
soft stock price and incorporate as much information into the model. Out of correla‐
ted assets, technical indicators, and fundamental analysis (discussed in the section
before), we will focus on correlated assets as features in this case study.8
For this case study, other than the historical data of Microsoft, the independent vari‐
ables used are the following potentially correlated assets:
Stocks
IBM (IBM) and Alphabet (GOOGL)
Currency9
USD/JPY and GBP/USD
Indices
S&P 500, Dow Jones, and VIX
The dataset used for this case study is extracted from Yahoo Finance and the FRED
website. In addition to predicting the stock price accurately, this case study will also
demonstrate the infrastructure and framework for each step of time series and super‐
vised regression–based modeling for stock price prediction. We will use the daily
closing price of the last 10 years, from 2010 onward.
