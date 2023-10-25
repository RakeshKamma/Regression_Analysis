# House Price Prediction Project

This repository contains a house price prediction project using various regression models. The goal of this project is to predict house prices based on different features, and we have implemented several regression models to find the most accurate one.

## Table of Contents
- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Regression Models](#regression-models)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Comparison](#model-comparison)
- [Results](#results)
- [Conclusion](#conclusion)

### Introduction

In this project, we aim to predict house prices using various regression models. We have employed different techniques and strategies to preprocess the data, engineer features, and assess the performance of each model. This README provides an overview of the project and its key components.

### Libraries Used

We have used the following Python libraries for this project:

- NumPy
- Pandas
- TensorFlow
- Scikit-learn

### Regression Models

We have implemented several regression models to predict house prices, including:

- Multiple Linear Regression (MLR)
- Polynomial Regression (PR)
- Support Vector Machines (SVR)
- Decision Trees (DT)
- Random Forest Regressor (RFR)
- Artificial Neural Network (ANN)
- XG Boost (XGB)
- Cat Boost (CB)

### Data Preprocessing

The dataset is preprocessed using various techniques, such as one-hot encoding, label encoding, and a correlation matrix analysis to handle categorical variables and assess feature relationships.

### Feature Engineering

We have employed feature scaling, dimensionality reduction, and grid search cross-validation to find optimal hyperparameters for the models.

### Model Comparison

We have created a regression template that compares different models to evaluate their performance. The metrics used for comparison are:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R^2)

### Results

After comparing the models, it was found that Support Vector Machines (SVR) performed the best for our dataset in terms of accuracy.

### Conclusion

This project demonstrates the process of house price prediction using various regression models and showcases the importance of data preprocessing, feature engineering, and model selection. The results suggest that SVR is the most suitable model for this specific dataset.

Feel free to explore the notebooks and code in this repository to get a deeper understanding of the project. If you have any questions or suggestions, please don't hesitate to reach out.

Happy modeling! 🏡📈
