# Bulldozer-price-prediction

## 1. Problem defition

 How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

## 2. Data

The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evaluation

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

## 4. Features

Kaggle provides a [data dictionary](https://github.com/rohanj98/Bulldozer-price-prediction/blob/main/data/Data%20Dictionary.xlsx) detailing all of the features of the dataset.

## Modelling:
I have used [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) from Scikit-learn library 

## Hyperparamter Tuning
Tuning the paramters of of our model to improve predictoin accuracy.

A walkthrough notebook for the project can be found [here](https://github.com/rohanj98/Bulldozer-price-prediction/blob/main/bulldozer-price-prediction.ipynb)
