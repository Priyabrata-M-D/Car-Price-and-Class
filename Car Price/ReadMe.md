# Car Price Prediction
## Introduction
This project aims to develop machine learning model for predicting price of cars.
Manual predictions can be time-consuming and may not result in optimal decisions.
The model will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format,
identifying the distribution of features, and leveraging regression based models, specifically the decision tree based algorithm,
to predict the car price accurately.

## Regression models details
Here different models were tested namely:
* GradientBoostingRegressor
* RandomForestRegressor
* AdaBoostRegressor
* DecisionTreeRegressor
* LinearRegression
* SVR
From above models Decision tree Regressor model performed better with a score of 0.904

## Steps involved
* Explored Null values and treated them
* Transformed the data into a suitable format and performing any necessary cleaning and pre-processing steps.
* Explored skewness and outliers in the dataset and are treated with log_transformation, capping outliers and
  visualization is also provided.
* Developed a machine learning regression model which predicts the price using the decision tree Regressor.

## Requirements
This project requires the following libraries to be installed:

* NumPy
* Pandas
* Scikit-learn
* vs code with jupyter extension

## Getting Started
* Clone the repository.
* Install the required libraries.
* Run the vs-code with jupyter extension or thefile is provided in repo also.
