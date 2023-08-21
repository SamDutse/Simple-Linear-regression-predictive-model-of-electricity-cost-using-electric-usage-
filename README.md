# Electric Cost Prediction Using Linear Regression

This repository contains code to predict electric costs using linear regression. The project achieved an impressive accuracy of approximately 98% in predicting electric costs based on usage data. 

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Visualization](#visualization)
- [Conclusion](#conclusion)

## Introduction
Electric cost prediction is an important task in energy management and budgeting. This project employs linear regression to predict energy costs based on usage data. Linear regression is a simple yet effective method for modeling the relationship between variables.

## Getting Started
To run the code and experiment with the project, you need to have the required libraries installed. You can install them using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Data Exploration
The project begins by importing necessary libraries and reading the electric usage data from a CSV file. The dataset contains information about usage, date, year, month, day, start time, end time, usage, units, and cost.

## Data Preprocessing
The dataset is explored using various methods like `head()`, `tail()`, `shape`, `info()`, and checking for missing values. The data is then split into features (`USAGE`) and the target (`COST`). The data is also split into training and testing sets using the `train_test_split` function from `scikit-learn`.

## Model Building
A linear regression model is imported and instantiated. The model is then trained on the training data using the `fit()` method. After training, the model is used to predict the electric costs on the test data.

## Model Evaluation
The performance of the model is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. These metrics provide insights into how well the model's predictions align with the actual electric costs.

## Visualization
The project includes visualizations to help understand the data and model performance. Box plots are used to visualize the distribution of energy usage and cost, both with and without outliers. Additionally, a scatter plot with a regression line is used to visualize the relationship between predicted and actual costs.
![](image.png)

## Conclusion
This project showcases the implementation of a linear regression model for predicting electric costs based on energy usage. With an accuracy of around 98%, the model proves to be effective in estimating costs. The combination of data exploration, preprocessing, model building, evaluation, and visualization demonstrates a comprehensive approach to predictive modeling in the energy domain.
