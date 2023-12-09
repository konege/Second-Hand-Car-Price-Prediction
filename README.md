# Second-Hand-Car-Price-Prediction

## Overview

This project aims to predict the selling price of cars based on various features like year of manufacture, present price, kilometers driven, fuel type, seller type, transmission type, and car age. The project uses a dataset containing these features and applies machine learning techniques for prediction. Two models, Multiple Linear Regression and Random Forest Regression, are compared, with hyperparameter tuning performed on the Random Forest model to optimize its performance.

## Requirements

This project requires the following libraries:
-NumPy
-Pandas
-Matplotlib
-Seaborn
-Scikit-learn
-MLflow

## Dataset

I took it from kaggle website.
Dataset: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv
Dataset file: car_data_csv

## Models and Techniques Used

-Data Preprocessing: Handling missing values, encoding categorical variables, feature selection, and data splitting.
-Multiple Linear Regression: A baseline regression model.
-Random Forest Regression: An ensemble model used for regression.
-Hyperparameter Tuning: Using RandomizedSearchCV to optimize the Random Forest model.
-MLflow: Used for tracking experiments, logging parameters, metrics, and models.

## Results

The performance of the models is evaluated using the R-squared metric. The Random Forest model with hyperparameter tuning yielded better results compared to the Multiple Linear Regression model.
