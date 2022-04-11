# Housing Price Prediction 
Helping US-based housing company named Surprise Housing to understand the pricing dynamics of a Australian housing market and predict selling prices

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


## General Information
### Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia

### Business Problem 
Model the price of houses with the available independent variables using Linear Regression with regularization. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.


## Conclusions
- Lasso Regression uses significantly less number of independent variable for the model (only 29 out of total 50 from Recursive Feature Elimination)
- Yet Lasso is able to explain the data relatively better. R squared value and Root Mean Squared Error is comparable to that of Ridge regression, merely 0.0004 lesser R2 score and 0.001 greater rmse for training data
- Ridge Model outperforms Lasso for the test data. But trading off complexity vs model fit, I would go for Lasso based Regression model


## Technologies Used
 
Python 3.x

### Python Libraries
- pandas - version 1.1.4
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- sklearn - version 1.0.2
- statsmodels - version 0.13.1

## Contact
Created by [@SathishKumarRamasamy](https://github.com/SathishKumarRamasamy) - feel free to contact me!
