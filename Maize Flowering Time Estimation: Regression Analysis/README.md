# Maize Flowering Time Estimation: Regression Analysis

## Objective

The goal was to find variables that were strongly correlated with the target variable, which was the time taken to flower. Various methods were tried, 
including Pearson's correlation, Lasso, Ridge, and linear regression, and random forest regression. 

## Dataset

This project involved selecting variables from a large dataset (feature importance) of Maize Flowering time, which had around 200x25 breeds with 5000 observations and 7393 variables. 

## Evaluation and Results
After examining the results, it was found that Random Forest Regressor with Pearson's correlation worked well on the dataset. We got a R2 score of 0.77 with a RMSE value of 3.14, which can be considered as a decent fit. The important features are 'Geno_code', 'pop' along with the marker data columns ('m434', 'm435', 'm436'..more) implying that these parameters played a huge role in predicting the response appropriately.
