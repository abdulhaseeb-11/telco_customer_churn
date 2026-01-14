# Telco Customer Churn Analysis

## Overview
This project analyzes customer churn in a telecommunications company using machine learning techniques. The analysis aims to identify key factors that influence customer retention and predict which customers are likely to churn.

## Dataset
The dataset used is `WA_Fn-UseC_-Telco-Customer-Churn.csv`, which contains information about telecom customers including:
- Demographic information
- Service subscriptions
- Account information
- Churn status

## Analysis Steps
The Jupyter notebook `telco_customer_churn.ipynb` performs the following analysis:

1. **Data Loading and Cleaning**
   - Load the customer churn dataset
   - Handle missing values and data type conversions

2. **Exploratory Data Analysis**
   - Visualize correlations between features and churn
   - Examine relationships between contract types, charges, and churn rates

3. **Data Preprocessing**
   - Encode categorical variables
   - Handle class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

4. **Model Training**
   - Split data into training and testing sets
   - Train a machine learning model (Random Forest) to predict churn

5. **Model Evaluation**
   - Generate classification report
   - Create confusion matrix
   - Analyze feature importance to identify key churn drivers

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

## Installation
```bash
pip install pandas matplotlib seaborn scikit-learn imbalanced-learn
```

## Usage
1. Ensure the dataset file `WA_Fn-UseC_-Telco-Customer-Churn.csv` is in the same directory as the notebook
2. Open `telco_customer_churn.ipynb` in Jupyter Notebook or JupyterLab
3. Run the cells in order to execute the analysis

## Key Findings
The analysis identifies the most important factors contributing to customer churn, helping telecom companies focus retention efforts on high-risk customers.

## License
This project is for educational purposes.
