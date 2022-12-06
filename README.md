# Advance_Regression_Anubhav_Mishra
# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
We are required to build a regression model using regularisation (l1 norm & l2 norm) in order to predict the actual value of the prospective properties and decide whether to invest in them or not. We have to identify the following

- which features are significant in predicting the price of a house
- how well those features describe the price of a house
- optimal value of strength of penalty (λ) for ridge and lasso


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn


## Conclusions
Highlights of the final model:
- We choose lasso as our final model over ridge
- Lasso's predictive r2_score is 90% whereas for ridge it is 88%
- Lasso model is lighter as it uses only 161 features whereas ridge uses all 215
