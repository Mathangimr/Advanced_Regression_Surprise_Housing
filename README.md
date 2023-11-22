# Surprise Housing
> To build model to predict the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- Background - The company wants to know:
			* Which variables are significant in predicting the price of a house, and
			* How well those variables describe the price of a house.
			* Determine the optimal value of lambda for ridge and lasso regression.
- Business Problem - The aim of this case study is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Dataset - Dataset provided in a csv file

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The top features which are common in both the models, that are best suited for price prediction for the house are below.
* GrLivArea
* Neighborhood_Crawfor
* SaleType_New
* OverallQual
* Neighborhood_NridgHt
* SaleCondition_Normal
* TotalBsmtSF
* OverallCond
* MSZoning_RL
* CentralAir_Y
- Based on the above selected features, we can decide how well each of them influence the SalePrice, either positively or negatively.

For Example, SaleCondition_Normal - This variable indicates that when there is a normal sale happening, then there is a chance of that the price of the house increase 1.06 times.

- Determine the optimal value of lambda for ridge and lasso regression
Optimal value of alpha for Ridge regression is 10
Optimal value of alpha for Lasso regression is 0.001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Matplotlib - version 3.7.0
- Pandas 	 - version 1.5.3
- Numpy  	 - version 1.23.5
- Seaborn 	 - version 0.12.2
- Sklearn	 - version 1.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is solely contributed by the author - @[Mathangimr]


## Contact
Created by @[Mathangimr] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
