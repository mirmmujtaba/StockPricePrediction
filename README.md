# Predicting Future Trends in Stock Prices
This project uses historical stock prices from Yahoo Finance to predict future trends in the stock prices of Apple Inc. The machine learning model used for this project is a linear regression model. The model is trained on the data from 2016 to 2020 and is used to predict the stock prices for the years 2021 and 2022.

### Dependencies
This project requires the following dependencies to be installed:

numpy
pandas
scikit-learn
yfinance
matplotlib

### Dataset
The dataset used in this project is obtained from Yahoo Finance using the yfinance Python library. The data includes the following features:

Date
Open
High
Low
Close
Adj Close
Volume

### Data Preprocessing
Before the data can be used to train the machine learning model, it is preprocessed in the following way:

A new column called 'target' is created to represent the stock price of the next day
The last row containing NaN value for the target is dropped
The data is split into training and testing sets

### Machine Learning Model
The machine learning model used for this project is a linear regression model.

Evaluation Metrics
The performance of the model is evaluated using the root mean squared error (RMSE) and the R-squared metric.

Results
The results of the model are visualized using the matplotlib library.
