# Surprise Housing _Case study
**Problem Statement and Business Objective:**

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:-
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Top 5 most important predictor variables are 
1>'OverallQual_9',
2>'OverallCond_9',
3>'OverallQual_8',
4>'GrLivArea',
5>'Neighborhood_Crawfor'

- Optimal value for Ridge regression is 8 and for Lasso regression is 0.001.

- Ridge Regression R2 Square are:-
  
   Train Data R2 square value is 0.94354265961746 and for Test data R2 square value is 0.8944768674326166

- Lasso Regression R2 Square are:-

   Train Data R2 square value is 0.9424639532374802 and for Test data R2 square value is 0.8885944800228901

- Normal distribution of error terms:-
   
  our model error terms following a normal distribution.

- Homoscedasticity check

  The data points are spread across equally without a prominent pattern, it means the residuals have constant variance (homoscedasticity)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- library 1 -pandas

-library 2- matplotlib

-library 3- warnings

-library 4 -numpy

-library 5 -seaborn

-library 6- sklearn

-library 7-statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.

This project is completed after successfully completing the Advance learning session module provided by IIITB & UpGrad .


## Contact
Created by [@PrakashShri] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
