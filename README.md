# Surprise Housing Company Price prediction using Advanced Linear Regression
> Surprise Housing Company prediction in prices of houses using Advanced Linear Regression - Lasso and Ridge Regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Surprise Housing Company - A US-based housing company, has decided to enter the Australian market for which it would require prediction of the actual value of the prospective properties and decide whether to invest in them or not.
- The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The objective of this assignment is to model the prices of houses with the available independent variables. This model would then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model would be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model performance using Ridge Regression (for lambda 9) was better in terms of R2 values of Train and Test, it’s better to use Lasso, as it brings and assigns a zero value to insignificant features, enabling us to do feature selection with significant predictor variables.

- Linear equation with Lasso for optimum Lambda '0.001' :
SalesPrice = 10.81 + x1 * 0.043 + x2 * -0.003 + x3 * -0.041 + x4 * 0.025 + x5 * -0.004 + x6 * -0.033 + x7 * 0.037 + x8 * 0.03 + x9 * 0.001 + x10 * -0.012 + x11 * 0.013 + x12 * -0.01 + x13 * 0.001 + x14 * 0.111 + x15 * -0.021 + x16 * -0.027 + x17 * -0.056 + x18 * -0.013 + x19 * 0.037

- Top 10 features with Lasso (lambda 0.001) are OverallCond_9, Neighborhood_Crawfor, OverallQual_9, SaleCondition_Partial, Functional_Typ, OverallCond_8, SaleCondition_Normal, Neighborhood_StoneBr, OverallCond_7 and OverallQual_8.

- Top 10 features with Ridge (lambda 9) are OverallCond_9, Neighborhood_Crawfor, Functional_Typ, OverallCond_8, OverallQual_9, Neighborhood_StoneBr, SaleCondition_Normal, SaleCondition_Partial, OverallQual_8 and MSZoning_FV.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References : referred Upgrad previous sessions on EDA, ML-1 and 2


## Contact
Created by [@sahuipsita] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
