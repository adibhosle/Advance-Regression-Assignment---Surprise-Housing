# Advance Regression Assignment - Surprise Housing
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

This assignment is a programming assignment wherein we have to build a Advance linear regression model of Lasso & Ridge for the prediction of price of houses.


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal: 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.



## Technologies Used
- Python Libraries for visualising, training & Testing model. Such as - numpy, pandas , lasso, ridge, sklearn, seaborn, matplotlib, etc.
- Jupyter Notebook 
- Github



## Conclusions
- Top 5 variables that are significant as well as how those variables describe the price of a house:
  1. GrLivArea: an increase of 1 square foot of house area above ground, the price will increase by 1.08 to 1.10 times.
  2. Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.08 to 1.09 times.
  3. OverallQual_8 & OverallQual_9: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.07 to 1.08 times.
  4. Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.06 to 1.07 times.
  5. Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.06 to 1.07 times.
  
- Results -

  Metric             Ridge Regression	    Lasso Regression
		
  R2 Score (Train)  	  0.935201            0.914017
  R2 Score (Test) 	    0.920952            0.919032
  RSS (Train) 	        8.149486            10.813744
  RSS (Test)	          2.729937            2.796244
  MSE (Train)	          0.006977            0.009258
  MSE (Test)	          0.009349            0.009576
  RMSE (Train)	        0.083530            0.096220
  RMSE (Test)	          0.096691            0.097858



## Acknowledgements
- Upgrade Learning
- Upgrade Faculty
- Aditya Bhosle


## Contact
Created by [Aditya Bhosle](https://github.com/adibhosle) - feel free to contact me!
