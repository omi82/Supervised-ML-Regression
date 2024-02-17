# Supervised-ML-Regression
This repository contains a machine learning regression model developed to predict the stock price of Yes Bank based on historical data.

 **Project Summary -**  This project aims to predict the closing price of Yes Bank stocks using supervised machine learning regression techniques. The project utilizes various libraries such as pandas, numpy, matplotlib, and scikit-learn for data manipulation, analysis, and model building.

**Data Preprocessing:**

1. Import the dataset containing historical stock prices.
2. Clean and prepare the data by handling missing values, scaling features, and selecting relevant features.

**Model Training and Evaluation:**

1. Split the data into training and testing sets.
2. Train various regression models such as Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Gradient Boosting Regressor.
3. Evaluate the performance of each model using metrics like mean squared error, R-squared score, and mean absolute error.

**Visualization:**

1. Plot the actual closing prices and predicted closing prices for the test set.
2. Compare the performance of different models and select the best performing model based on the evaluation metrics.

**Conclusion:**

The project successfully demonstrates the application of supervised machine learning regression techniques for predicting the closing price of Yes Bank stocks. The best performing model is chosen based on its accuracy andgeneralizability.

# **Problem Statement**
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time Series models or any other predictive models can do justice to such situations. This Dataset has monthly stock prices of the bank since its inception and includes closing, opening, highest and lowest stock prices of every month. The main objective is to predict the closing stock price of the month.

**VARIABLE DESCRIPTION-** In the given dataset there are 185 rows and 5 features, Features descriptions are as follows-

Date-: Date denotes the date of investment(date contains month and year for a particular price.)

Open-: It is the price at which a stock started trading.

High-: It is the highest price at which a stock is traded during a period.

Low-: It is the minimum price at which a stock is traded during a period.

Close-: The closing price refers to a stock's trading price closed at the end of a trading day. It's a dependent variable that we need to predict from our respective ML models. The closing price is calculated as the weighted average price of the last 30 minutes, i.e. from 3:00 PM to 3:30 PM in case of equity.

OBJECTIVE- The objective of this project is to predict the yes bank stock closing price of the month which includes the following steps-

1-  Loading the data into a data frame.

2-  Cleaning the data.

3-  Exploratory analysis and visualizations.

4-  Feature Manipulation and Selection.

5-  Train Test Split.

6-  Model Implementation.

7-  Selecting the best model.

8-  Model Deployment.
