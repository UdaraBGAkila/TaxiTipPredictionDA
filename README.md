# TaxiTipPredictionDA

1. Executive Summary

1.1. Task

Building a predictive model for the tip amount of taxi trips in New York City. 

1.2. Data Background

The data set used contains features of taxi trips in New York City. The trip records for yellow taxis have fields that record the pick-up and drop-off times and locations, trip distances, itemized fares, rate kinds, payment methods, and driver-reported passenger counts. The technology companies approved under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP) collected and supplied the data utilized in the linked datasets to the NYC Taxi and Limousine Commission (TLC).

1.3. Approach/Methods Used

To build a predictive model, three models will be created using test data and they will be evaluated using test data. The three models are built on following regression techniques.
1.	Multiple Linear Regression
2.	Random Forest Regression
3.	Decision Tree Regression

1.4. Results

After training and testing the above models with given data sets, random forest regression model emerged as the best out of three with high score in training data, high r2 score and low mean squared error compared to the other 2 models for predicting tip amount. 
