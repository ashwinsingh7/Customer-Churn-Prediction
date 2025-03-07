# Predicting Customer Churn Using Machine Learning

Google Colab notebook can be found here - https://colab.research.google.com/drive/1bebH082uVuyI9XG1KmSEz-E2gCdb-ES3?usp=sharing 

## Project Overview
Customer churn is a critical issue for businesses, as losing customers leads to revenue loss and increased acquisition costs. This project leverages machine learning models to predict customer churn, helping businesses implement targeted retention strategies.

## Problem Statement
Many companies struggle with identifying customers who are likely to leave. By predicting churn in advance, businesses can take proactive measures such as offering promotions, improving service quality, or personalizing customer engagement. The goal of this project is to develop a predictive model that accurately classifies customers into 'churn' and 'non-churn' categories.

## Data Source
The dataset contains customer demographic details, service usage behavior, contract details, and churn labels. It is sourced from Kaggle.

## Project Workflow
### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables 
- Feature scaling (where necessary)
- Removing highly correlated features to avoid redundancy

### 2. Exploratory Data Analysis (EDA)
- Distribution of churned vs. non-churned customers
- Correlations between features
- Feature distributions

### 3. Model Selection
Three machine learning models were implemented:
- **Logistic Regression:** Serves as a baseline model, offering interpretability and efficiency.
- **Decision Tree:** Captures non-linear relationships but is prone to overfitting.
- **Random Forest:** An ensemble method that enhances decision trees by reducing variance and improving generalization.

### 4. Model Training and Evaluation
Models were evaluated using:
- **Confusion Matrix, Precision, Recall, and F1-Score** (to assess predictive quality)
- **ROC-AUC Score** (to compare classification performance across thresholds)


The results showed that the **Random Forest model achieved the highest AUC score, outperforming Logistic Regression and Decision Tree.**

