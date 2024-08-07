# Laptop price calculation based on historical data

This repository contains files and database for an ML project that preidcts the price of laptops using previous sales data. The data base consists of information about laptop brands, laptop specs and their actual prices.
The jupyter notebook file includes python codes which performs extensive data cleaning and EDA on the uncleaned data, performs data visualization and extracts functional data insights. 
ML modelling is executed by making use of various supervised learning algorithms provided by SciKit Learn library such as LinearRegression, LassoRegression, RidgeRegression, DecisionTreeRegressor and RandomForest. Of all the algorithms used RanomForestRegressor came with the highest accuracy. The model had an accuracy score of 0.87 and was able to predict the laptop prices with an average accuracy of 87%.
The VSCode files contain a Django web app based on our ML model, designed with Streamlit UI. The Webapp is later deployed in the Heroku cloud. All code files for the necessary operation are included in this repository.
