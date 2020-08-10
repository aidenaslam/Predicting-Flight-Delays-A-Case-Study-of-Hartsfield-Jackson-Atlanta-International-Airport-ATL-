# Predicting Flight-Delays: A Case Study of Hartsfield Jackson Atlanta International Airport ATL (Master's Thesis)
The US aviation industry in the last decade has experienced an ever-increasing demand of passengers. This is requiring airports to evaluate their current strategies and be able to adapt to changing industrial environments to not only provide a better service towards airlines and passengers, but to maximise profit through efficient operation. One way to achieve this is by efficiently organising and handling airport capacity. The aim of this study was therefore, to implement deep learning to accurately predict the arrival delay of flights at ATL in the US to assist with airport capacity planning for the ever-increasing passenger demand.

## Exploratory Data Analysis

* 


## Data Preparation
* Flight delay dataset sourced from Bureau of Transportation Statistics (BTS) [1] and weather data sourced from Iows Environmental Mesonet (IEM) [2] for the years 2016-2018

* No missing values for the BTS dataset and missing values for the weather dataset imputed using the daily mean or monthly mean.

* Feature selection carried out using F-Score, Pearson's correlation coefficient and recursive feature elimination (RFE).

* Outliers defined as flights delayed greater than 400 minutes during the severe weather events in January, April and December.

* Numerical features standardised to reduce effecr of outliers and categorical variables transformed using one-hot-encoding

* Dataset split into training, validation and testing for the years 2017, 2016 and 2018 respectively. 

## Model Building and Asessment

* Baseline models:
  * average arrival delay: 12.5 minutes
  * multi-layer perceptron (MLP) without activation function: RMSE of ... and MAE of ....

* Grid search implemented to identify best combination of hyperparameters for MLP with 1-3 hidden layers

## Evaluation

## Conclusions and Future Work

## References
