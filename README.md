# Housing Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model 
using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
	o) Which variables are significant in predicting the price of a house, and
	o) How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
It is required to model the price of houses with the available independent variables. This model will then be used by 
the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy 
of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management 
to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- For Ridge Regression,optimum value of alpha is 10,and the 5 most important variables are
  OverallQual	0.097246
  GrLivArea	 0.086398
  TotalBathroom	 0.072405
  NoRidge	0.067924
  KitchenQual	0.065265
- For Lasso Regression,optimum value of alpha is 0.001,and the 5 most important variables are
  GrLivArea	0.238502
  OverallQual	0.191577
  TotalBathroom	0.065602
  NoRidge	0.064293
  KitchenQual	0.062701

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas 1.3.5
- numpy 1.21.5
- seaborn 0.12.2
- sklearn 1.0.2
- statsmodels 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the lectures and live session conducted by Upgrad & IIIT Bangalore.
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sandipm26] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->