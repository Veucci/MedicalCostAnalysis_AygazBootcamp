# Aygaz Makine Öğrenmesi Bootcamp - Medical Cost Analysis Project

This repository contains the code and analysis for the "Medical Cost Analysis" project, conducted as a part of the Aygaz Makine Öğrenmesi Bootcamp. The project aims to analyze medical insurance cost data and develop a predictive model to estimate medical insurance charges based on various features.

## Table of Contents
- [Introduction](#introduction)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Selection](#model-selection)
- [Hyper-parameter Optimization](#hyper-parameter-optimization)
- [Model Evaluation](#model-evaluation)

## Introduction
The project utilizes Python programming language and various data analysis and machine learning libraries. It involves the following steps:

1. **Exploratory Data Analysis (EDA):** This section explores the dataset to gain insights and understand the distribution of variables. It includes data visualization using histograms, bar plots, heatmaps, and more.

2. **Data Preprocessing:** In this step, the dataset is prepared for modeling. It involves handling categorical variables using label encoding and one-hot encoding, splitting the data into training and testing sets, and applying standard scaling.

3. **Model Selection:** Several regression models are considered for predicting insurance charges. Linear Regression, Ridge Regression, Lasso Regression, Random Forest Regressor, and Support Vector Regressor are evaluated using cross-validation.

4. **Hyper-parameter Optimization:** The best performing model is selected, and hyper-parameter optimization is performed using GridSearchCV to fine-tune the model's hyper-parameters.

5. **Model Evaluation:** The final model is evaluated on the test set using various regression evaluation metrics, such as Mean Squared Error (MSE), Mean Absolute Error (MAE), R-squared Score, Median Absolute Error, and Explained Variance Score.

## Exploratory Data Analysis
EDA involves exploring the dataset to understand its structure and relationships between variables. Key visualizations include histograms, bar plots, line plots, heatmaps, and scatter plots. The analysis provides insights into BMI distribution, relationships between features like smoker and charges, region and children, age and BMI, and more.

## Data Preprocessing
Data preprocessing involves preparing the dataset for machine learning. Categorical variables are transformed using label encoding and one-hot encoding. The dataset is split into training and testing sets, and standard scaling is applied to the features.

## Model Selection
Several regression models are considered, including Linear Regression, Ridge, Lasso, Random Forest Regressor, and Support Vector Regressor. Cross-validation is used to evaluate and compare the models' performance.

## Hyper-parameter Optimization
The best-performing model is selected from the previous step, and hyper-parameter optimization is performed using GridSearchCV to find the optimal hyper-parameter values for the model.

## Model Evaluation
The final model is evaluated on the test set using various regression evaluation metrics. This step provides insights into how well the model predicts medical insurance charges based on the given features.

Feel free to explore the Jupyter Notebook file "MedicalCostAnalysis_colab.ipynb" to see the detailed code, visualizations, and results of each step.

For any questions or further information, please open a issue.
