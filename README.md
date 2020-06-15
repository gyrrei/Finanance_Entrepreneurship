# Finanance&Entrepreneurship
Correlation analysis between the financial stock market and the founding of new companies. 

## Does financial crisis spur entrepreneurship?
Norway experienced financial crashes in 2008, 2011, 2014/15, and in 2018.

* Hypothesis 1:
There is a natural correlation between the financial state of a country (financial optimism) and the foundation of new companies

* Hypothesis 2:
After significant financial crashes, such as the one in 2008, there is an increase in companies founded after this

## Datasets
* Enhetsregisteret – Norwegian Registry of Businesses
Founding date of every business/startup registered in Norway from 1995 until today

* Oslo Børs Benchmark Index – Norwegian Stock Exchange
Daily OSEBEX from 1995 until today, and comprise the most traded shares representing the financial state

## Results
* Pearson’s Correlation Coefficien
Test whether there is a linear relationship between financial optimism and number of founded companies 
Results: p = 0.934 - probably depended

* Kwiatkowski-Phillips-Schmidt-Shin
Test whether the time series is trend stationary or not
Results:  p = 0. 045 - probably not stationary

* For change in stock market prices* < 0
Pearson coef: p = 0.04 - No correlation 

* For change in stock market prices > 0
Pearson coef: p = 0.96 - Highly correlated

There is a clear positive increase in number of companies founded the month after  a positive change in the stock market.

As we can see from the figure, outliers exists for high increase in stock prices and for high decrease, which requires further analysis of the time series and other factors.


A part of the CDTM Statistical Data Analyis elective.
