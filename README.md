# Module 19 - Neural Network Charity Analysis

## Overview 
Predict if applicants to Alphabet Soup will be successful through neural networks.  

## Results
#### What variable(s) are considered the target(s) for your model?
-"IS_SUCCESSFUL" column, this is the baseline for if money was put to go use or not

#### What variable(s) are considered to be the features for your model?
EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


#### What variable(s) are neither targets nor features, and should be removed from the input data? 
"EIN", this variable was dropped and not needed. 

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
3 layers
--100 neurons
--75 neurons
--10 neurons


#### Were you able to achieve the target model performance?
Yes, accuracy was 78.57%, above the goal of 75%.

#### What steps did you take to try and increase model performance?
-Increased layers
-Bucketed "NAME" column to find names appearing less than 6 times.


## Summary
A deep learning model was created that was able to reach predictive accuracy of 78.57%, above the goal of 75%.

![stacked_launch_outcomes](https://github.com/charlieburd/neural_network_charity_analysis/blob/main/resources/image%20(37).png)
