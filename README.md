# Amazon-Stock-Price-Prediction

The task is to predict the day price direction of Amazon.com, Inc. (AMZN) stock.

The stock market is very complex and highly volatile. In order to be profitable, we do not need to predict the correct price, but rather, the price direction: whether it will be higher or lower than the price that is today. If we predict it to be higher, we might as well buy some stocks, else, we should probably sell.

Therefore, the target would be a binary classification whether the next day closing price will be higher than the opening price.

Data Description

We have data for the period from 1997 up to year 2020 that we have split that into training (1997-2016), validation (2016-2018) and testing (2018-2020) periods. The data is available in the AMZN_train.csv, AMZN_val.csv and AMZN_test.csv files, respectively.

Each dataset has the same format with the following 7 columns:

Date - in format YYYY-MM-DD
Open - stock price upon opening of an exchange
High - the highest stock price on a given day
Low - the lowest stock price on a given day
Close - stock price at the end of a trading day
Adj Close - adjusted closing price that takes into account corporate actions
Volume - the amount of shares traded over the course of a trading day



Define, train and evaluate a predictive model that takes as the input the data provided. Do not use external data for this project. You may use any algorithm of your choice or compare multiple models.

Make sure that the solution reflects your entire thought process - it is more important how the code is structured rather than the final metrics. You may assume that any model resulting in AUC > 0.515 will be enough. 
