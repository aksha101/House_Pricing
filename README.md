#ADVANCED REGRESSION#

SURPRISE HOUSING

Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

The company wants to know:
What all variables are significant in predicting the price of a house and how well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

##Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


The steps followed to solve this problem are:

1. Reading, understanding and visualising the data
2. Data cleaning
3. Preparing the data for modelling(train-test split, rescaling etc.)
4. Model building
5. Model evaluation

##Conclusion:

These variables are significant in predicting the price of a house :
BsmtFinSF2 : Type 2 finished square feet , 
LotShape : General shape of property , 
ExterCond : Evaluates the present condition of the material on the exterior ,
GarageCars : Size of garage in car capacity , 
Neighborhood_Gilbert : Physical locations within Ames city limits(Gilbert) ,
BsmtFinSF1 : Type 1 finished square feet ,
OverallQual : Rates the overall material and finish of the house , 
BsmtExposure : Refers to walkout or garden level walls ,
CentralAir : Central air conditioning ,
OverallCond : Rates the overall condition of the house .

