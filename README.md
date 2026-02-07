# Multiple-linear-regression
This project implements Multiple Linear Regression to predict company profit using factors like R&amp;D Spend, Administration, and Marketing Spend. It includes data preprocessing, visualization, model training, evaluation, and model saving using Python and Scikit-learn, demonstrating a complete ML workflow.
Overview

This project demonstrates the implementation of Multiple Linear Regression (MLR) to predict company profit based on multiple independent variables such as R&D Spend, Administration Cost, and Marketing Spend. The project follows a complete machine learning pipeline from data preprocessing to model saving.

# Dataset

The dataset contains information about startups and their spending in different departments.

# Features:

R&D Spend

Administration

Marketing Spend

State (Categorical Feature)

Target:

Profit

Dataset File:

50_Startups.csv

# Algorithm Used

Multiple Linear Regression is used to predict output based on multiple input variables.

# Equation:
Y = b0 + b1X1 + b2X2 + b3X3 + ... + bnXn


Where:

Y → Predicted Profit

X → Independent Variables

b → Coefficients

# Technologies & Libraries

Python

NumPy

Pandas

Matplotlib

Scikit-learn

Pickle

# Project Workflow
1️⃣ Importing Libraries

Libraries required for data handling, visualization, and model building.

2️⃣ Loading Dataset

Dataset is loaded using Pandas.

3️⃣ Data Preprocessing

Handling categorical data using encoding

Splitting dataset into training and testing sets

4️⃣ Model Training

Multiple Linear Regression model is trained using Scikit-learn.

5️⃣ Prediction

Model predicts profit using testing dataset.

6️⃣ Model Evaluation

Model performance is analyzed by comparing predicted and actual values.

7️⃣ Model Saving

# Trained model is saved as:

finalized_model_MLR.sav
