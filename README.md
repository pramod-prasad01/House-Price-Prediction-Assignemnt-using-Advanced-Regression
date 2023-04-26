# Project Name

### House-Price-Prediction-Assignemnt-using-Advanced-Regression




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
**Business Objective** :
An US based company wants to expand their business to Australian Market. They want to understand the factors impacting the price of houses so they can buy them below their actual price and sell at higher price. Using the features they want to identify the potential properties they should buy.

**Business Problem** : The company wants to understand :

* Which features contribute towards price of Houses.
* How well those features explain the price

**Business Goal** : Need to create a model that explains the price of the houses using idependent variable availble in dataset.
The model will be used by management to understand how price varies with respect to those variables. Accordingly they can form their strategies to get high returns.


## Technologies Used
- python3
- Jupyter Notebook
- python libraries - pandas, numpy, seaborn, matplotlib, sklearn


## Conclusions
After using Lasso and Ridge Regulaziation techniques, the following are the most important features which can be used to predict the house price:
1. The optimal value for alpha for Ridge is 4 and Lasso is 0.0001.
2. The higher values of positive coeficients suggest a high sale value.
 * GrLivArea	
 * MSZoning_FV	
 * OverallCond
 * TotalBsmtSF	
 * MSZoning_RH
 * MSZoning_RL
 * MSZoning_RM
 * LogLotArea

3. The higher values of negative coefficients suggest a decrease in sale value.Some of those features are:
 * OverallQual_PO	
 * Age

4. Lastly,when the market value of the property is lower than the Predicted Sale Price, its the time to buy.


## Acknowledgements
- This project was inspired by Course in ML and AI from IIITB and Upgrad


## Contact
Created by [@pramod-prasad01] - feel free to contact me!


