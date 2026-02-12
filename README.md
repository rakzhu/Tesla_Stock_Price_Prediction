Tesla Stock Price Prediction using XGBoost
# Project Overview

This project builds a machine learning model to predict Tesla (TSLA) closing stock prices using historical time-series data. The workflow includes data preprocessing, feature scaling, sequence generation using sliding window technique, model training with XGBoost, and evaluation using regression metrics.
The goal is to demonstrate practical implementation of time-series forecasting using machine learning techniques in Python.

# Technologies Used

Python
Pandas
NumPy
Plotly (Visualization)
Scikit-learn
XGBoost
Matplotlib
Seaborn

# Project Workflow

Data Loading and Cleaning
Date Conversion & Renaming Columns
Exploratory Visualization
Feature Scaling (MinMaxScaler)
Train-Test Split (70%-30%)
Time Series Dataset Creation (Sliding Window)
Model Training using XGBoost Regressor
Prediction & Evaluation (MAE, RMSE)

# Model Details

Algorithm: XGBoost Regressor
Estimators: 1000
Time Step Window: 15 days
Train/Test Split: 70/30
Evaluation Metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

# Results

The model successfully learns time-based price patterns and produces predictions evaluated using regression error metrics.

# Key Learning Outcomes

Time series data preprocessing
Sliding window feature engineering
Feature scaling for ML models
Regression model training
Model evaluation for forecasting problems
Financial data visualization
