# Surprise Housing - House Prices Prediction - Advanced Regression Assignment
## Problem Statement:

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.



The company wants to know:

-   Which variables are significant in predicting the price of a house, and
-   How well those variables describe the price of a house.


## Business Goal:
> You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Need to model, the price of houses, with the available independent variables. This model will then be used by the Company to understand how exactly the prices vary with the variables.

#### train.csv
-   This is the dataset which is used to build the model to drive the inferences.

#### data_description.txt
-   This file consists description of variables and their meaning explaining the dataset of (train.csv file).

#### Subjective Questions.pdf
-   It contains the question and answers to the subjective questions.    


## Conclusions
We have used regularisation techniques like Ridge and lasso to predict the target variable.

- Ridge regression optimal alpha value - `7`
- Lasso regression optimal alpha value - `0.001`

The variables significant in predicting the price of a house are:

- Neighborhood_StoneBr
- RoofMatl_WdShngl 
- Neighborhood_NoRidge 
- Neighborhood_NridgHt
- GrLivArea



## Technologies Used
- python - version 3.9.1
- numpy - version 1.23.4
- matplotlib - version 3.6.2
- seaborn - version 0.12.1
- scikit-learn - version 1.2.0
- statsmodels - version 0.13.5
- jupyter notebook - version 6.5.2
- missingno - version 0.5.1


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad and IIIT Bangalore
- Upgrad course learning content, live session and Google search.


## Contact
Created by Kanchan Singh [@kanchansingh1123](https://github.com/kanchansingh1123) - feel free to contact me!