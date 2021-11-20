# boston-housing-prediction-ml-app :house_with_garden:

 This app predicts housing prices in Boston, and is developed using Python and Streamlit.

 App: [Boston Housing Price Prediction] (https://house-price-predict-ml.herokuapp.com/)
 The dataset can be downloaded from [Boston Housing Price Dataset] (https://archive.ics.uci.edu/ml/datasets/Housing)

## Introduction

This study aims to find the important factors that affect the house prices in a certain area. The Boston housing price dataset is used as an example in this study. This dataset is part of the UCI Machine Learning Repository, and you can use it in Python by importing the sklearn library or in R using the MASS library. This dataset contains 13 factors such as per capita income, education level, population composition, and property size which may have influence on housing prices. This study will first conduct an exploratory data analysis on the dataset and then use multiple linear regression to try to predict housing prices and determine the importance of each feature.


## Data
 Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository1): CRIM: per capita crime rate by town.

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