# House Price Prediction Using Machine Learning

## Overview

This project develops a Machine Learning solution for predicting residential house prices based on housing characteristics and amenities. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization.

## Dataset

* Dataset: Housing.csv
* Records: 545
* Features: 13
* Missing Values: 0
* Duplicate Records: 0

## Features Used

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

## Project Workflow

1. Data Cleaning and Validation
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Visualization
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Feature Importance Analysis

## Models Implemented

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

## Model Performance

| Model             | MAE       | RMSE      | R² Score |
| ----------------- | --------- | --------- | -------- |
| Gradient Boosting | 945,253   | 1,287,074 | 0.6723   |
| Linear Regression | 970,043   | 1,324,507 | 0.6529   |
| Random Forest     | 1,014,947 | 1,399,769 | 0.6124   |

### Best Model

Gradient Boosting Regressor achieved the highest predictive performance with an R² score of 0.6723.

## Key Insights

* Area is the most influential factor affecting house prices.
* Bathrooms have a strong impact on property value.
* Air conditioning contributes significantly to price increases.
* Parking availability positively influences house prices.
* Unfurnished houses generally have lower market values.

## Visualizations

The project includes:

* Price Distribution Analysis
* Area Distribution Analysis
* Correlation Heatmap
* Price vs Area Relationship
* Price vs Bedrooms Analysis
* Price vs Bathrooms Analysis
* Price vs Stories Analysis
* Feature Importance Analysis
* Actual vs Predicted Price Comparison
* Model Performance Comparison

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook


