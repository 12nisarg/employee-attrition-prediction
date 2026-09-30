# Employee Attrition Prediction Using Machine Learning

## Project Overview

This project develops a machine learning-based HR analytics solution to predict employee attrition risk and support proactive employee retention decisions.

The project uses employee-level HR data and Logistic Regression to estimate the probability of employee attrition and identify key factors associated with employee turnover.

## Problem Statement

Organizations often rely on historical attrition reports and reactive retention strategies. This project applies predictive analytics to identify employees who may be at higher risk of leaving and help HR managers design targeted retention interventions.

## Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

- 1,470 employee records
- 35 original variables
- Target variable: Attrition
- Binary classification problem

## Methodology

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Removal of non-informative variables
4. Categorical variable encoding
5. Train-test split
6. Feature scaling using StandardScaler
7. Logistic Regression model development
8. Model evaluation
9. Attrition probability prediction
10. Employee risk classification
11. Visualization and interpretation

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Logistic Regression
- Machine Learning Classification

## Model Performance

The Logistic Regression model achieved:

- **Accuracy:** 87.98%
- **ROC-AUC:** 0.82

## Key Insights

The analysis identified several factors associated with higher employee attrition risk, including:

- Overtime
- Frequent business travel
- Longer periods since last promotion
- Certain job roles
- Distance from home

The model converts predictions into employee-level attrition probabilities that can be used as a decision-support input for HR teams.

## Project Structure

```text
employee-attrition-prediction/
│
├── Attrition_code (1).ipynb
└── README.md

Disclaimer

This project is an academic machine learning project using a publicly available HR analytics dataset. The predictions are intended for analytical and educational purposes and should not be used as an automated basis for employment decisions.

Author

Nisarg Khatawkar

MBA – Business Analytics
Indian Institute of Management Ranchi
