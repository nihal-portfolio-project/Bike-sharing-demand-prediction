# Bike-sharing-demand-prediction
Performed an analysis using Supervised Machine Models to predict the count of Bike Sharing Demand.
# Project Title : Bike_Sharing_Demand_Prediction_Project
# Problem Description:
 Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
 # Steps Involved
 1- Exploratory Data Analysis
 
 2- Data preprocessing and cleaning
 
 3- Feature Engineering( introducing new coloumns and features)
 
 4- Model building - Built following models
 
                     Linear Regression
                     
                     Lasso Regression
                     
                     Ridge Regression
                     
                     DecisionTree Regressor
                     
                     RandomForest Regressor
                     
                     Gradient Boost
                     
                     Xg Boost
                     
                     
 
 5- Model Evaluation- Evaluated the models based on following metrics
 
                      Mean Squared Error
                      
                      Root Mean Squared Error
                      
                      R-Squared
                      
                      Adjusted R-Squared
                      
# Conclusions:
 
 1.As it was stated in the problem, rented bike count was low in 2017 untill november. After that rented bike count started increasing.
 
 2.There was sharp increase in demand from the end of 2017 that too in winter season of the year. The demand however decrease at the end of 2018.
 
 3.Bike count rent is highly correlated with 'Hour', which seems obvious. Demand for bike is mostly in morning (7 to 8) and in the evening (3 to 9).
 
 4.After doing exploratory data analysis, applying Linear Regression model didn't go quite well as it gave only 67.109325% accuracy.
 
 5.Lasso and Ridge Regression helps to reduce model complexity and prevent over-fitting which may result from simple linear regression. with Lasso, ridge and    ElasticNet regressor We got r squared value of 0.67106525, 0.67109331, 0.67109188 respectively.
 
 6.With Decision Tree we are able to achieve the r2 score of 0.811.
 
 7.Random forest regressor gave r squared value of 0.911 on test data
 
 8.Gradient Boost gives higher value of R squared metric in train data 0.947 and on test data it is 0.912
 
 9.XG Boost gave r squared value of 0.9164
 
 10.XG Boost came with best accuracy to approximate numbers of rented bikes demand. It gives amazing results of training r-square at 0.97 and test r-square value at 0.9164 also with adjusted r-square with 0.911.
 
 
