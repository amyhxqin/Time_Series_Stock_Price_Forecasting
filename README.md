# Time_Series_Stock_Price_Forecasting

### Created by [Amy Qin](https://github.com/amyhxqin)
### This project is not for commercial purpose. All data belong to their rightful owner.

## Introduction
In this exercise, we will predict the price of a seasonal stock through time series forecasting with Facebook's Prophet in Python. A seasonal stock is a type of stock whose price is highly correlated to the consumer demand during a specific time of the year. This is usually a stock from businesses such as airlines and hotel chains. In this notebook, we will attempt to predict the stock price of the former, namely of Air Canada (AC.TO).

## Goal
Evaluate the accuracy of time series forecast with Prophet and suggest adjustements to improve

## Analysis
The analysis, including code and diagrams, can be found in the notebook titled seasonal_stock_prediction.

## Conclusion
Time series forecasting with Prophet predicts relatively accurately the general trend of a seasonal stock's price during a year. However, it is vulnerable to anomalies caused by extrinsic macroeconomic factors. It is thus recommended to remove these anomalies from the training data. The prediction is also less accurate for long periods of time (more than a month). Apart from seasonality, many factors lead to fluctuations in a seasonal stocks' price. This explains the difficulty in making an accurate prediction. It is thus recommended to only pay close attention to the predicted prices closer to the dates of the training data.

Adjustements to improve the model require a deeper understanding of macroeconomy and the stock market. This knowledge can be used to improve the current model, for instance by changing the criteria for the training data set, or to combine the current model with other machine learning algorithms, such as for language processing. A thorough analysis of stock sentiment from news and social media can possibly improve the accuracy of the current model.

## Resources
(What is a seasonal stock?)[https://www.timothysykes.com/blog/seasonal-stocks/]
(Data Source)[https://finance.yahoo.com/quote/AC.TO/history?p=AC.TO&.tsrc=fin-srch]
(Prophet)[https://research.fb.com/prophet-forecasting-at-scale/]
