---
layout: default
---
# **Stock Price Prediction for JPMorgan Chase & Co**

Predicted the stock price of JPMorgan Chase & Co at 12/31/2019. Performed **Time Series, Linear Regression and Random Forest Regression models**.

Due to the complications of the date change, I used the beginning of 2020 (01/01/2020) to predict the stock price at the end of 2019 (12/31/2019). Since the variables that formed the model are interest rate, GDP, unemployment rate, CPI, etc., which can hardly change in one day, I believe these data would not interfere much for my final prediction.

Furthermore, because most of my indicators are recorded monthly, I used interpolation to better fit the model. Since all of them are rates, I applied the same number to the entire month/quarter. 

The datasets I used are as followings:
* Historical Stock Price [source: Yahoo Finance](https://finance.yahoo.com/quote/JPM/history?p=JPM)
* GDP [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/CPIAUCSL)
* Interest Rate [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/FEDFUNDS)
* Inflation Rate [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/T10YIE)
* Unemployment Rate [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/UNRATE)
* Consumer Interest [source: fred.stlouisfed.org](https://fred.stlouisfed.org/series/CPIAUCSL)

In this group project, our goal is to recommend food for different users by predicting ratings for food recipes based on the rating history of each users. We used the dataset from Kaggle: [Project Dataset: foodrecsysv1](https://www.kaggle.com/elisaxxygao/foodrecsysv1).

During the process, we cleaned and manipulated the data, identified the most important variables, came up with our own features, and build the prediction model using KNN. We also applied GridSearch in order to get the optimal combination for our model with the highest prediction accuracy.

The one of the unique features about our model is it can change throughout time. **The model itself is not fixed.** People's preferences may change, so should the prediction models.

## Code
Please see the [Jupyter Notebook](http://htmlpreview.github.io/?https://github.com/Yiting2018/Recommendations-for-Food/blob/gh-pages/documents/Recipe_rating_prediction.html) for details.

### [Go Back to Homepage](https://yiting2018.github.io)

## Slides
#### [Download PDF](https://github.com/Yiting2018/Recommendations-for-Food/raw/master/documents/Recipes_Rating_System.pdf)
<img src="./documents/PowerPoint/1.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/2.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/3.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/4.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/5.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/6.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/7.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/8.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/9.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/10.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/11.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/12.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/13.jpg" width="1000" height = "400" alt="" />
<img src="./documents/PowerPoint/14.jpg" width="1000" height = "400" alt="" />

### [Go Back to Homepage](https://yiting2018.github.io)
