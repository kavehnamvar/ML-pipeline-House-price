# ML-pipeline-House-price
# Adavanced House Price Prediction

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, you can predict the final price of each home.

## Practice skills
- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting

## Goal
To predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

## Metric
Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

### Dataset Description

The problem and its dataset is from a kaggle competition.
Link of the dataset: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

There is a train.csv, test.csv, a data_description.txt which is a full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here, and finally a sample_submission as a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms.