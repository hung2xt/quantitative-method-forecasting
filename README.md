## quantitative-method-forecasting
1. Using Supervised method to predict a stock price
#### Problem definition: 
In the supervised regression framework used for this case study, the weekly return of Microsoft stock is the predicted variable. We need to understand what affects Microsoft stock price and incorporate as much information into the model. Out of correlated assets, technical indicators, and fundamental analysis, we will focus on correlated assets as features in this case study. For the purpose of personal research, other than the historical data of Microsoft, the independent variables used are the following potentially correlated assets:
  - Stocks: IBM (IBM); Alphabet (GOOGL)
  - Currency: USD/JPY; GBP/USD
  - Indices:S&P 500; Dow Jones; and VIX

The dataset used for this case study is extracted from Yahoo Finance and the FRED website. In addition to predicting the stock price accurately, this case study will also demonstrate the infrastructure and framework for each step of time series and supervised regression–based modeling for stock price prediction. We will use the daily closing price from 2010 to 2022.

##### Notebook: https://github.com/hung2xt/quantitative-method-forecasting/blob/main/StockPrice.ipynb

2. Using Effecient Frontier to find portfolio optimization
#### Problem definition:
In this topic, I use efficient frontier to create stock portfolio for 4 public companies: APPL (Apple Inc), AMZN (Amazon.com Inc), GOOGL (Alphabet Inc Class A), NKE (Nike Inc).
And then we can search for most efficient porfolio with minimal volatility and for risky portfolio with the highest Sharpe Ratio.

Some important information to note about Sharpe Ratio:
A higher Sharpe ratio is generally considered to be better. The Sharpe ratio is a measure of risk-adjusted return, which means that it takes into account both the amount of return an investment generates and the amount of risk it takes to generate that return. A higher Sharpe ratio indicates that an investment is generating more return for each unit of risk it takes on.

A Sharpe ratio of 1 is considered to be average, while a Sharpe ratio of 2 or higher is considered to be good. A Sharpe ratio of 3 or higher is considered to be excellent.

However, it is important to note that the Sharpe ratio is not the only measure of investment performance. Other factors, such as the investment's volatility and its historical performance, should also be considered.

Here are some additional information about Sharpe Ratio:

The Sharpe ratio is named after William Sharpe, who developed it in the 1960s.
The Sharpe ratio is calculated by dividing the investment's excess return by its standard deviation.
The excess return is the investment's return minus the risk-free rate.
The standard deviation is a measure of the investment's volatility.
The Sharpe ratio is a useful tool for comparing the risk-adjusted performance of different investments. It can also be used to track the performance of an investment over time.

Here are some examples of Sharpe ratios for different investments:

The S&P 500 index has a Sharpe ratio of about 0.8.
The MSCI EAFE index has a Sharpe ratio of about 0.7.
The Barclays Aggregate bond index has a Sharpe ratio of about 0.4.
The average actively managed mutual fund has a Sharpe ratio of about 0.3.
As you can see, the Sharpe ratios for different investments vary widely. This is because different investments have different levels of risk and return.

It is important to note that the Sharpe ratio is not a perfect measure of investment performance. It is only one factor that should be considered when making investment decisions.

##### Notebook: https://github.com/hung2xt/quantitative-method-forecasting/blob/main/EfficientFrontier.ipynb
