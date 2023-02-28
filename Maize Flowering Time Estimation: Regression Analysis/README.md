# Maize Flowering Time Estimation: Regression Analysis

## Objective

The goal was to find variables that were strongly correlated with the target variable, which was the time taken to flower. Various methods were tried, 
including Pearson's and Spearman's correlation, Lasso, Ridge, and Elastic Net regression, linear regression, and random forest regression. 

## Dataset

This project involved selecting variables from a large dataset (feature importance) of Maize Flowering time, which had around 200x25 breeds with 5000 observations and 7393 variables. 

## Evaluation and Results
After examining the results, it was found that Random Forest Regressor with Pearson's correlation worked well on the dataset.The best model had an RMSE value of 3.7 and an R2 statistic of 77%, indicating a good fit for the dataset.