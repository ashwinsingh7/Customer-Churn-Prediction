# Predicting Customer Churn using Machine Learning

Google Colab notebook can be found here - https://colab.research.google.com/drive/1bebH082uVuyI9XG1KmSEz-E2gCdb-ES3?usp=sharing 

## Project Overview
Customer churn is a critical issue for businesses, as losing customers leads to revenue loss and increased acquisition costs. This project leverages supervised machine learning models to predict customer churn, helping businesses implement targeted retention strategies.

## Problem Statement
Many companies struggle with identifying customers who are likely to leave. By predicting churn in advance, businesses can take proactive measures such as offering promotions, improving service quality, or personalising customer engagement. The goal of this project is to develop a predictive model that accurately classifies customers into 'churn' and 'non-churn' categories based on the available data.

## Data Source
The dataset contains cellular usage data including customer demographic details, service usage behavior, contract details, and churn labels. It is sourced from Kaggle.

<img width="300" alt="Screenshot 2025-03-27 at 12 09 16 PM" src="https://github.com/user-attachments/assets/1207ff84-def2-4862-83c4-f801749c1a3a" />


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

<img width="350" alt="Screenshot 2025-03-27 at 12 10 10 PM" src="https://github.com/user-attachments/assets/ed2cfd39-d130-4eb7-9d17-febed468ad31" /> 
    <img width="350" alt="Screenshot 2025-03-27 at 12 13 07 PM" src="https://github.com/user-attachments/assets/d921af81-83de-4570-be21-8de50ae7eac4" />


### 3. Model Selection
Three machine learning models were implemented:
- **Logistic Regression:** Serves as a baseline model, offering interpretability and efficiency.
- **Decision Tree:** Captures non-linear relationships but is prone to overfitting.
- **Random Forest:** An ensemble method that enhances decision trees by improving generalisation.

<img width="450" alt="Screenshot 2025-03-27 at 12 09 36 PM" src="https://github.com/user-attachments/assets/62e46e57-2ce0-41b2-bf22-cb79aca753a7" />


### 4. Model Training and Evaluation
Models were evaluated using:
- **Confusion Matrix, Precision, Recall, and F1-Score** (to assess classification accuracy)
- **ROC-AUC Score** (to compare classification performance across thresholds)
- **Feature Importance** was also assessed based on the Random Forest classifier and it showed that total daytime minutes and customer service calls were the most important features

<img width="500" alt="Screenshot 2025-03-27 at 12 17 13 PM" src="https://github.com/user-attachments/assets/1c59e953-2e74-4ca5-9511-abbcb9d1b8f1" />



The results showed that the **Random Forest model achieved the highest AUC score, outperforming Logistic Regression and Decision Tree** models; it also achieved the highest classification accuracy of 94%.

