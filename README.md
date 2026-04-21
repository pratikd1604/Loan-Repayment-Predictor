# Loan-Repayment-Predictor

**Overview**

This project focuses on predicting whether a borrower will repay a loan or not using an Artificial Neural Network (ANN) and Machine Learning models. The goal is to assist financial institutions in making better lending decisions by identifying high-risk applicants in advance.

Loan repayment prediction is a critical problem in the banking and finance domain, as it helps reduce non-performing assets (NPAs) and improves profitability by minimizing default risk

**Objective**

-Build a classification model to predict loan repayment status
-Perform data preprocessing and feature engineering
-Train an ANN model and machine learning models for improved prediction accuracy
-Evaluate model performance using appropriate metrics

**Dataset**
Lending Club Dataset obtained from Kaggle - https://www.kaggle.com/wordsforthewise/lending-club

The dataset consists of borrower-related financial and personal information such as:

Income and employment details
Loan amount and interest rate
Credit history and financial behavior
Debt-to-income ratio and other risk indicators

These features play a significant role in determining repayment ability.

**Tech Stack**

Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Machine Learning: Scikit-learn
Environment: Jupyter Notebook

**Project Workflow**

1. Data Preprocessing
  Handling missing values
  Encoding categorical variables
  Feature scaling using StandardScaler

2. Exploratory Data Analysis (EDA)
  Univariate and bivariate analysis
  Identifying patterns and correlations
  Visualizing important features

3. Feature Engineering
  Selection of relevant features
  Transforming variables for better model performance

4. Model Building
  Input layer, hidden layers, and output layer
  Activation functions (ReLU)
  Random Forest
  XGBOOST

 ANN models are widely used for classification tasks due to their ability to capture complex patterns in data.

5. Model Evaluation
  Accuracy
  Loss curves
  Confusion matrix
  Precision and Recall

**Visualisation**

<img width="1032" height="726" alt="image" src="https://github.com/user-attachments/assets/43691ad9-8381-4721-aff4-da59d33f0ca6" />


**Model Comparison**

Model	                |  Accuracy
----------------------------------
Logistic Regression	  |  82%
Random Forest	        |  85%
ANN 	                |  89%

**Results**

  -The ANN model achieved an accuracy score of 89%, which is the highest among all the models tested in this project
  -Demonstrates strong performance in predicting loan repayment behavior
  -Effectively identifies high-risk borrowers, making it suitable for real-world financial applications
