# Surprise Housing - Advanced Regression Assignment

Surprise Housing, a US-based housing company, has made the decision to enter the Australian market. 
The business buys homes for less than their actual value and sells them for more using data analytics. 
The business has gathered a set of data from Australian home sales for the same objective.

## Table of Contents
-Data understanding and exploration
-Data Cleaning
-Data Visualization
-Data Preparation
-Model building and evaluation


## General Information

Business Objective:

The goal is to use the available independent variables to model the cost of homes. The management will then utilize this model to determine exactly how the prices fluctuate depending on the variables. As a result, they can influence the company's strategy and concentrate on areas that will provide large returns. The model will also help management better understand how prices change in a new market.

Business need to evaluate below points-

Important factors for estimating the price of a house.
How effectively these factors accurately reflect the price of a house.

Goals:

To model the cost of homes using the relevant independent variables.
To understand the precise relationship between price variation and variable.
To have an impact on the company's strategy and direct attention to areas that will yield high returns on investment.

## Conclusions

**Ridge Regression Analysis Results:

- Optimal alpha value : 7.0
- Mean Squared Error (MSE) on train set : 0.0104
- Mean Squared Error (MSE) on test set : 0.0139
- R-squared value on train set : 0.9187
- R-squared value on test set : 0.8882


**Lasso Regression Analysis Results:

- Optimal alpha value : 0.0004
- Mean Squared Error (MSE) on train set : 0.0106
- Mean Squared Error (MSE) on test set : 0.01411
- R-squared value on train set : 0.9167
- R-squared value on test set : 0.8868

Since Lasso Regression can help in feature reduction Thus we will make our model based on Lasso regression.

Below are predictors which are highly important to predict the sales of the house using Lasso Regression.

Neighborhood_Crawfor : Physical locations within Ames city limits (Crawford)
GrLivArea : Ground floor Living Area
OverallQual : Rates the overall material and finish of the house
TotalBsmtSF : Total square feet of basement area
OverallCond : Rates the overall condition of the house
Condition1_Norm : Proximity to various conditions (Normal)
Foundation_PConc : Type of foundation (Poured Contrete)
Neighborhood_BrkSide : Physical locations within Ames city limits (Brookside)
Neighborhood_Somerst :Physical locations within Ames city limits (Somerset)
SaleType_New : Type of sale (Home just constructed and sold)
Neighborhood_NridgHt : Physical locations within Ames city limits (Northridge Heights)



## Technologies Used
- Python : 3.8.5
- jupyter-notebook : 6.1.4
- matplotlib : 3.3.2
- statsmodels :  0.12.0
- seaborn  :  0.11.0


## Acknowledgements

- References 
https://www.google.com/search?q=bias+variance+tradeoff&sxsrf=ALiCzsaCoy5gSf8T5S-MWATFQ_CMDdcCwA:1669821858848&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjo9u-Vm9b7AhXHiv0HHfp5CTUQ_AUoAXoECAMQAw&biw=1536&bih=746&dpr=1.25#imgrc=YsL9Gotqa3p-yM
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html


## Contact
Created by simranjit- Kaur - feel free to contact me!


