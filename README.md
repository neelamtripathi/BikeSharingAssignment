# Bike Sharing Assignment
> Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.



They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.




## Table of Contents
1. Reading and Understanding Data
-Data Quality Checks
-Visualizing Continuous Variables
-Outliers in Continuous Variables
-Visualizing Categorical Variables
-Correlation

2. Data Preparation
-Creating Indictor Variables
-Splitting data set into Test & Train subsets
-Scaling Numerical Features

3. Modelling
-Recursive Feature Elimination
-Manual Elimination
-Model 1
-Model 2
-Verifying MultiCollinearity
-Final Model

4.Residual Analysis

5.Prediction
6.Model Evaluation
7.Model Stability
8.Top Features

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- What is the business probem that your project is trying to solve?
Business Goal: You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Analysis is carried out using a Mixed Feature Selection Approach. 15 features are selected algorithmically using Recursive Feature Elimination. Further selection is done manually by looking at multicollinearity and statistical significance of features and overall fit of the model. The 13 most significant features to understand demand have been reported.

The data set is randomly divided into training and test data. Final Model built on training data set explains 84% of the variability and achieves 81% on test data.
The final relationship between demand and predictors is as follows.

cnt = 4527.31685981 + 2000.813889 yr + 685.560556 Saturday + 625.322329 winter + 586.229282 september  - 890.3115 july -561.583892 Mist_cloudy + 513.321998 workingday -1341.146803 hum -1100.976725 spring + 4099.972163 atemp -791.687695 windspeed -2051.379041 light snow/rain.

where atemp , windspeed and hum are normalized.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->





## Contact
Created by neelamtripathi - feel free to contact me!


