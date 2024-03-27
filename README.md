# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. 
 The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 

    The company wants to know:

	Which variables are significant in predicting the price of a house, and
        How well those variables describe the price of a house.

## Table of Contents
* [Bussiness Goal](#bussiness-goal)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)



## Bussiness Goal
-We need to model the price of houses with the available independent variables. 
 This model will then be used by the management to understand how exactly the prices vary with the variables. 
 They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
 Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
1.R2 score for Lasso is slightly higher that Ridge Regression.So considering Lasso model.
2.RMSE for lasso is slighlty lower than ridge.
3.The Variables significant in predicting the price of a house are
	1. GrLivArea
	2. OverallQual
	3. TotalBsmtSF
	4. LotArea
	5. Street_Pave
	6. TotRmsAbvGrd
	7. YearBuilt
	8. YearBuilt

## Technologies Used
- python
- matplotlib
- sklearn
- seaborn

