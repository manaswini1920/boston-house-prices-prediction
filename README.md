# boston-housing-prediction-streamlit app:

 This app predicts housing prices in Boston, and is developed using Python and Streamlit.

App : https://boston-house-price-uncc.herokuapp.com/ 

## Introduction

This study aims to find the important factors that affect the house prices in a certain area. The Boston housing price dataset is used as an example in this study. This dataset can be imported from the sklearn library. This dataset contains 13 factors such as per capita income, education level, population composition, and property size which may have influence on housing prices. This study will first conduct an exploratory data analysis on the dataset and then use multiple linear regression and Random Forest Regression to try to predict housing prices and determine the importance of each feature and finally select a model that best performs.


## Data
 Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows:

1.  CRIM: Per capita crime rate by town
2.  ZN: Proportion of residential land zoned for lots over 25,000 sq. ft
3.  INDUS: Proportion of non-retail business acres per town
4.  CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5.  NOX: Nitric oxide concentration (parts per 10 million)
6.  RM: Average number of rooms per dwelling
7.  AGE: Proportion of owner-occupied units built prior to 1940
8.  DIS: Weighted distances to five Boston employment centers
9.  RAD: Index of accessibility to radial highways
10. TAX: Full-value property tax rate per $10,000
11. PTRATIO: Pupil-teacher ratio by town
12. B: 1000(Bk — 0.63)², where Bk is the proportion of people of African American descent by town
13. LSTAT: Percentage of lower status of the population
14. MEDV: Median value of owner-occupied homes in USD 1000's

## Exploratory Data Analysis
 Understanding the correlation of features between target and other features.
 ![image](https://user-images.githubusercontent.com/40575189/142949185-36cc0828-6c39-4e56-84eb-0bf0276ebc42.png)

 No missing values.
 ![image](https://user-images.githubusercontent.com/40575189/142949215-e2b27421-aedb-452f-a97c-b9cd1dcd1001.png)

 Median value of the owner occupied houses(MEDV) ranges from 5 to 50
 Average number of rooms per dwelling ~6
 The full value property-tax rate varies from 187 -711
 The columns age and number of blacks are highly left skewed.
 The average number of rooms per dwelling is normally distributed.
 There are more dwellings which have lower median value than number of dwellings that have higher  value( medv is right skewed)
 lstat is right skewed.
 
 ## Feature Selection
 Apply SelectKBest class to extract top 5 best features

