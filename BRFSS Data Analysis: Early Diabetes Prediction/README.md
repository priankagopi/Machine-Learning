# BRFSS Data Analysis : Early Diabetes Prediction

## Objective

To develop a data model to predict diabetes and perform feature selection to detect diabetes at an early stage. The aim is also to perform imputation and exploratory analysis.

## Dataset description

The Behavioural Risk Factor Surveillance System (BRFSS) is a national survey that collects health-related data by telephone about U.S. residents (adults +18 years old) regarding their health-related risk behaviours, chronic health conditions, and use of preventive services. The survey completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world. 

## Proposed Model

- The proposed model begins by importing the SAS dataset from the official BRFSS website for the sample year, 2021, which is the latest available data. 
- Data preprocessing steps are carried out to clean the data and make it suitable for exploratory data analysis (EDA) and modeling. The preprocessing steps include feature engineering, dropping irrelevant and duplicate columns, and handling missing values using imputation methods such as Iterative Imputer using Linear Regression. 
- Modeling is done using Logistic Regression, which is the baseline model, and improved results were obtained using Histogram Gradient Boosting Classifier algorithm and Random Forest. 
- The model evaluation metrics used are Accuracy score, Confusion matrix, precision-recall, and F1 score, which are the best measures to evaluate a classification model. 
- Feature selection is then performed using the HG Boost algorithm, which shows the most correlated features for Diabetes.

## Evaluation and Result
The Random Forest Classifier has an accuracy of 93% while Logistic Regression shows accuracy of 84%. The best results are obtained by Histogram Gradient Boost algorithm which displayed the highest accuracy of 96.9%. Contrary to Logistic regression and 
Random Forest, which lack native support for data imputation and necessitate a data imputation phase, Histogram Boost gradient performed all data imputation on its own and gave outstanding results.