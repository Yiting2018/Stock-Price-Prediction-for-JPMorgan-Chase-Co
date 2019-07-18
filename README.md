---
layout: default
---
# **Stock Price Prediction for JPMorgan Chase & Co**

Predicted the stock price of JPMorgan Chase & Co at 12/31/2019. Performed **Time Series, Linear Regression and Random Forest Regression models**.

<img src="https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/img/0.png" width="1000" height = "300" alt="" />

Due to the complications of the date change, I used the beginning of 2020 (01/01/2020) to predict the stock price at the end of 2019 (12/31/2019). Since the variables that formed the model are interest rate, GDP, unemployment rate, CPI, etc., which can hardly change in one day, I believe these data would not interfere much for my final prediction.

Furthermore, because most of my indicators are recorded monthly, I used interpolation to better fit the model. Since all of them are rates, I applied the same number to the entire month/quarter. 

The datasets I used are as followings:
* [Historical Stock Price](https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/dataset/JPM.csv) [source: Yahoo Finance](https://finance.yahoo.com/quote/JPM/history?p=JPM)
* [GDP](https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/dataset/GDP.csv) [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/CPIAUCSL)
* [Interest Rate](https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/dataset/Effective%20Federal%20Funds%20Rate.csv) [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/FEDFUNDS)
* [Inflation Rate](https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/dataset/Inflation%20Rate.csv) [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/T10YIE)
* [Unemployment Rate](https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/dataset/UNRATE.csv) [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/UNRATE)
* Consumer Interest [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/CPIAUCSL)

During the process, I noticed that some of the variables have very strong correlations.

<img src="https://github.com/Yiting2018/Stock-Price-Prediction-for-JPMorgan-Chase-Co/blob/master/img/1.png" width="800" height = "800" alt="" />

In order to avoid multicollinearities, I only used interest rate, unemployment rate, and GPD.

## Code
Please see the [Jupyter Notebook](http://htmlpreview.github.io/?https://github.com/Yiting2018/Recommendations-for-Food/blob/gh-pages/documents/Recipe_rating_prediction.html) for details.

### [Go Back to Homepage](https://yiting2018.github.io)

## Slides
#### [Download PDF](https://github.com/Yiting2018/Recommendations-for-Food/raw/master/documents/Recipes_Rating_System.pdf)


### [Go Back to Homepage](https://yiting2018.github.io)
