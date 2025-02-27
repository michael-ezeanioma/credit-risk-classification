# Overview

Using Python, Pandas, Scikit-Learn, and Logistic Regression, this project analyzes credit risk by building a machine learning model to classify loans as either healthy (low risk) or high risk of default. The model is trained on historical lending data, evaluated using classification metrics, and assessed for its suitability in predicting loan outcomes.

# Project Components

__1. Data Preprocessing:__
Loads lending_data.csv into a Pandas DataFrame.
Defines labels (y) from the "loan_status" column:
0 → Healthy loan
1 → High-risk loan
Defines features (X) from the remaining columns.
Splits the data into training (X_train, y_train) and testing (X_test, y_test) datasets using train_test_split.

__2. Building the Logistic Regression Model:__
Initializes and fits a logistic regression model using training data.
Uses the trained model to predict loan risk on testing data.
Evaluates model performance using:
Confusion matrix to visualize correct and incorrect predictions.
Classification report to assess accuracy, precision, and recall.

__3. Credit Risk Analysis Report:__
Summarizes model performance using key classification metrics.
Evaluates the model’s ability to distinguish between healthy loans and high-risk loans.
Recommends (or rejects) the model for real-world use based on its predictive accuracy.

# Files

__credit_risk_analysis.ipynb:__ Jupyter Notebook with model development and evaluation.

__lending_data.csv:__ Dataset containing historical loan performance data.

# Key Features

__Data Preprocessing:__
Reads loan data and extracts target (y) and feature (X) variables.
Splits data into training and testing sets for model development.

__Logistic Regression Model:__
Trains a binary classification model to predict loan risk.
Generates predictions for new loan applications.
Evaluates performance with confusion matrix and classification report.

__Model Assessment:__
Analyzes model accuracy, precision, and recall.
Determines effectiveness in predicting high-risk and healthy loans.
Provides recommendations on model deployment.

# Dependencies

__Pandas:__ Reads and processes loan data.

__Scikit-Learn:__ Splits data into training/testing sets and builds the logistic regression model.

__Logistic Regression:__ Performs credit risk classification.
Confusion Matrix & Classification Report: Evaluates model accuracy.

# Technologies Used

__Python:__ Core programming language for data processing and model training.

__Pandas:__ Handles data manipulation and feature engineering.

__Scikit-Learn:__ Provides tools for regression modeling and performance evaluation.

# How to Use

1. Clone this repository to your local environment.
2. Load and preprocess loan data.
3. Train a logistic regression model.
4. Evaluate model accuracy and interpret results.
5. Review the Credit Risk Analysis Report for final recommendations.
6. 
<!--Mod 20-->
