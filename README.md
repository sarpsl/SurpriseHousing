# Surprise Housing - Advanced Regression
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Dataset:
Datset for this is provided by upGrad which contains 81 columns and 1460 rows. Accompanied by data-definition explaining the metadata of the dataset.

## Conclusions
Got the following r2 score for,
Ridge
- Train: 0.9212172818478634
- Test: 0.8793046041474403

Lasso
- Train: 0.9209786266433511
- Test: 0.8807280483737678

Selected Lasso model basing on the scores.

## Technologies Used
- Python - 3.9.17
- jupyterlab - 3.6.3
- numpy - 1.24.3
- pandas - 2.0.3
- matplotlib - 3.7.1
- seaborn - 0.12.2

## Contact
Created by Syed Abdul Rahim [@sarpsl] - feel free to contact me!
