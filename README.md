# Boston Housing Price Prediction
This project aims to predict housing prices in Boston using machine learning techniques. The dataset used in this project contains various features such as crime rate, average number of rooms, accessibility to highways, and more, for different regions in Boston, along with the corresponding housing prices.

- Dataset:
The dataset used in this project is boston.csv. It consists of 506 rows and 15 columns. Below are the columns present in the dataset:

 - CRIM: Per capita crime rate by town
 - ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
 - INDUS: Proportion of non-retail business acres per town
 - CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
 - NOX: Nitric oxides concentration (parts per 10 million)
 - RM: Average number of rooms per dwelling
 - AGE: Proportion of owner-occupied units built prior to 1940
 - DIS: Weighted distances to five Boston employment centers
 - RAD: Index of accessibility to radial highways
 - TAX: Full-value property tax rate per $10,000
 - PTRATIO: Pupil-teacher ratio by town
 - B: 1000(Bk - 0.63)^2 where Bk is the proportion of [people of African American descent] by town
 - LSTAT: Percentage of lower status of the population
 - PRICE: Median value of owner-occupied homes in $1000s

- Usage:
 - boston_housing_prediction.py: 
  - This script performs the following tasks:
   - Data loading and preprocessing.
   - Exploratory data analysis (EDA) using visualizations.
   - Training linear regression models to predict housing prices.
   - Evaluation of model performance using R-squared metric.
   - Prediction of housing prices for given property characteristics.
