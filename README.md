# INDIAN-HOUSE-PRICE-PREDICTION
In this project we are going to see the house details, construction area , resale status, latitude and longitude details and total price values of house. we have to predict the price of house that can be used find out the new house data .
# DATASETS
Collected from the kaggle
# APPROACH
* In this project, i have done exploratory data analysis for cleaning and removing the null values.
* I extracted the city from address column and map the city into three categorical variables and change into numeric using pandas dummies variable.
* I change the large values like square feet,longitude and latitude values into log values
* Finally, all the values in numeric types , i split the data into 70% train and 30% valid 
* Then all ML models like linear regression,decision tree and random forest used to train and valid the datasets
# RESULT
* Among all other ML models , random forest gives best results which are determined by r2_score and RMSE values
* The r2_score value of y_valid and preds is 0.9537994835228609
* The RMSE value of y_valid and preds is 142.35359981412972
 
