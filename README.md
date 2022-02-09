# Project Name
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Table of Contents
* [General Info](#general-information)
* [Libraries Used](#technologies-used)
* [Conclusions]

## General Information
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.
- Dataset used: train.csv which has the information of all variables which influence the house price
- Using the Mulitple Linear regression, Ridge and Lasso models, the plan is to identify the variables which are significant in predicting the house prices. Also, how well those variables explain the house price.


## Conclusions
- Optimal lambda(alpha) value for Ridge regression model is 2.0
- Optimal lambda(alpha) value for Lasso regression model is 0.0001
- All the models have R2 score around 95%
- Top 5 significant features from Ridge model
    - GrLivArea               
    - 1stFlrSF                
    - BsmtFinSF1              
    - OverallQual_9           
    - Neighborhood_StoneBr    
- Top 5 significant features from Lasso model
    - GrLivArea               
    - BsmtFinSF1              
    - OverallQual_9           
    - Neighborhood_StoneBr   
    - LotArea          
- Lasso model gave an R2 score very close to what Ridge regression model has given. But was also able to eliminate 142 features. 
- So, Lasso model should be preferred as it gave a good R2 score with lesser no. of features, keeping the model simpler compared to the model generated by Ridge regression or base linear regression models


## Technologies/Library Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- sklearn.model_selection
- sklearn.metric
- sklearn.preprocessing
- sklearn.feature_selection
- sklearn.linear_model

## Contact
Created by [@nareshmuniganti] - feel free to contact me!
