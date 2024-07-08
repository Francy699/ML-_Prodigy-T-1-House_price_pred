This project about Implement a linear regression model to predict the price of houses based on their square footage and the number of bedrooms and bathrooms.
In this project Machine learning librares are used such that numpy library for numericals ,pandas library used for Data importing, manipulation & analysis ,Matplotlib library used for 2D plotting and the most popular machine learning library which is free sofware ,it is a collection of algorithms for machine learning,easy to implement.
LINEAR REGRESSION FOR HOUSE PRICE PREDICTION
1.IMPORTING LIBRARIES
2.LOAD THE DATA
   Dataset Description
     train.csv - the training set
     test.csv - the test set
dataset containing house prices, square footage, number of bedrooms, and bathrooms.
Load this data into a pandas DataFrame.
DATA CLEANING
MODEL SELECTION
3.FEATURE SELECTION
Define the features (independent variables) that will be used for prediction.
In this case, features are:
Square footage
Number of bedrooms
Number of bathrooms
4.TARGET VARIABLES
Define the target variable (dependent variable) you want to predict.
Here, the target variable is the house price.
5.TRAIN THE MODEL
Create a linear regression model object.
Train the model using the features (X) and target variable (y).
6.MAKE PREDICTIONS
You can now use the trained model to predict house prices for new data points.
Create a DataFrame with new values for square footage, bedrooms, and bathrooms.
Use the model's predict method to get the predicted prices.
7.MODEL EVALUTION
Evaluate the performance of your model using metrics like R-squared or mean squared error.
This helps assess how well the model generalizes to unseen data.
