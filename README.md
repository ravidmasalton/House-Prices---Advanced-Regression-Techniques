# House-Prices---Advanced-Regression-Techniques
predicting house prices
## Project Overview
This project focuses on predicting house prices using advanced regression techniques. The dataset contains 81 features describing various properties of houses. The goal is to build a machine learning model that accurately predicts the sale price of a house based on these features. The project involves data preprocessing, feature engineering, model selection, and hyperparameter tuning.

  **Kaggle Notebook**: [Ravid's Notebook](https://www.kaggle.com/code/ravidmasalton/assignment2)

## Introduction
In this competition, we work with a dataset about houses, containing 81 features that describe different properties of each house. The objective is to create a machine learning model that can predict the sale price of a house using regression models.

## Data Preprocessing
To ensure the quality of the data, several preprocessing steps were performed:
- Removal of irrelevant features
- Handling missing values appropriately
- Addition of new features
- Data splitting using cross-validation

## Exploratory Data Analysis
Various visualizations and analyses were conducted to understand the distribution of features and their correlation with house prices.

## Model Selection
We evaluated several models to find the best one for predicting house prices:
1. **KNN (K-Nearest Neighbors)**
2. **Decision Trees**
3. **SVM (Support Vector Machines)**
4. **Ensemble Methods** (e.g., BaggingRegressor, AdaBoost)

## Optimal Model and Hyperparameters
### KNN
- **Best K**

### Ensemble Methods
- **BaggingClassifier**

## Feature Selection
- **Backward Selection**
- **Forward Selection**

## Hyperparameter Tuning
- **Grid Search vs Random Search**

## Summary
In our research, we tested various models and preprocessing techniques. Our final model, BaggingRegressor, provided the highest accuracy in predicting house prices. We also implemented feature compression using Principal Component Analysis (PCA) to improve model performance.

## Results
- **Best Accuracy Score**: 0.897 (with LWLR model)
