In this repository, we will analyze and understand how the sales of Hypermarket products would be in future in order to further research and maximize their profits.<br>
We have train (8523) and test (5681) data set. Train data set has both input and output variable(s). We need to predict the sales for test data set.

Variable Description -<br> 
Item_Identifier : Unique product ID<br> 
Item_Weight : Weight of product<br> 
Item_Fat_Content : Whether the product is low fat or not<br> 
Item_Visibility : The % of total display area of all products in a store allocated to the particular product<br> 
Item_Type : The category to which the product belongs<br>
Item_MRP : Maximum Retail Price (list price) of the product<br> 
Outlet_Identifier : Unique store ID<br>
Outlet_Establishment_Year : The year in which store was established<br> 
Outlet_Size : The size of the store in terms of ground area covered<br> 
Outlet_Location_Type :  The type of city in which the store is located<br> 
Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket<br> 
Item_Outlet_Sales : Sales of the product in the particulat store. This is the outcome variable to be predicted.

The project involves a whole process of creating machine learning models on the Hypermarket dataset. There are two .csv files for the training and testing of data, to make predictions. We began with exploratory data analysis using visualizations and obtained essential features for making best predictions. 
Imputed missing values and performed label encoding on categorical columns for predictive analysis. We saw that the Random Forest model gave the best results with a RMSE value of 1150.7 and R^2 score of 0.55.
