
# House Price Prediction Model

In this project, a machine learning model has been developed to predict house prices. The main stages of the project can be summarized as follows:

## Requirements

Includes libraries required to install and use the libraries and models used in the project.

## Dataset and Exploratory Data Analysis (EDA)

Dataset Reading and Merging: Train and test datasets have been read and merged.
Overview Function: A function has been written to display general characteristics of the dataset.
Capture Numerical and Categorical Variables: Numerical and categorical variables in the dataset have been identified.
Categorical Variable Analysis: Summaries of categorical variables have been shown, and their distributions have been visualized.
Numerical Variable Analysis: Summaries of numerical variables have been shown, and their histograms have been visualized.
Target Variable Analysis: The relationship between categorical variables and the target variable has been shown.
Correlation Analysis: Correlations between numerical variables have been shown.
Variables with High Correlation: Variables with high correlation have been identified.

## Feature Engineering

Outlier Analysis: A function has been written to identify and handle outlier values.
Missing Value Analysis: Functions have been written to visualize and fill missing values.
Rare Analysis and Encoder Application: Functions have been written to identify rare classes and apply the encoding process.
Creating New Variables: New features have been added to the dataset.

## Modeling

* Model Building: Models to be used have been determined, the dataset has been split into train and test sets, and RMSE values have been calculated using cross-validation on various models.
* Bonus: Log Transformation and Model Building: Log transformation has been applied to the target variable, and an RMSE value has been calculated using the LightGBM model.
* Hyperparameter Optimization: Hyperparameter optimization has been performed for the LightGBM model.
* Determining Variable Importance Level: Feature importance analysis has been conducted on the LightGBM model.

## Bonus: Kaggle Submission Preparation

* Making Predictions on Test Data: Using the LightGBM model, empty 'SalePrice' values in the test data have been predicted.
* Creating Submission File: A new dataframe has been created with predictions and saved to a CSV file suitable for submission on the Kaggle page.
