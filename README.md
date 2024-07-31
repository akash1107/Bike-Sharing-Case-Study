# Bike-Sharing-Case-Study
Linear Regression model to understand the business strategy how exactly the demands vary with different features
#Project Name :Bike Sharing

# Bike Sharing Problem Statement
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

The company wants to know:

a. Which variables are significant in predicting the demand for shared bikes
b. How well those variables describe the bike demands


You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions


1. We can consider the model 4, as it is having very low multicollinearity between the predictors and the p-values for all the predictors is significant. F-Statistics value of 206.5 (which is greater than 1) and the Prob (F-statistic) of 2.40e-143 i.e. almost equals to zero, states that the overall model is significant

2.const	0.4086
yr	0.2492
workingday	0.062
windspeed	-0.1946
Spring	-0.2653
SAT	0.0672
clear__Few_partly	0.0945
light_snow_light	-0.2148


From the Model 4  summary, it is evident that all our coefficients are not equal to zerowhich means We REJECT the NULL HYPOTHESIS

3.F-Statistics is used for testing the overall significance of the Model: Higher the F-Statistics, more significant the Model is.

F-statistic: 206.5
Prob (F-statistic): 2.40e-143
The F-Statistics value of 206 (which is greater than 1) and the p-value of '~0.0000' states that the overall model is significant

4. Observation

Graph shows test data and predicted data is linear. It means model is giving the accurate prediction.

r2 for test data is 0.7038172219590334
r2 for training data is 0.742


## Technologies/Library Used
1. pandas
2. numpy
3. matplotlib
4. seaborn






