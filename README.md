# Prediction the Sale Price of Bulldozers using Machine Learning   
[Jupyter notebook of the Project](https://github.com/a0n0k0i0t/https-github.com-a0n0k0i0t-bulldozer-price-prediction-project/blob/master/end-to-end-bulldozer-price-regression.ipynb)   
Predict the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers.

## 1.Problem
The goal is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

## 2.Data
The data is split into three parts:

<ul>
    <li>Train.csv is the training set, which contains data through the end of 2011.
    <li>Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 
    <li>Test.csv is the test set, which won't be released until the last week of the competition. It contains data from  May 1, 2012 - November 2012.
</ul>

## 3.Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
For more information:
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

## 4.Features
Check out the features of the dataset in Kaggle page "Data Dictornary.xlsx" which has infromation of all the features. https://www.kaggle.com/c/bluebook-for-bulldozers/data.
