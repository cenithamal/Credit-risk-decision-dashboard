# Credit Risk Decision Dashboard

## Overview
A credit risk scoring and approval policy simulation project that predicts borrower default risk, segments applicants by risk, and supports lending policy decisions through a Power BI dashboard.

## Business Problem
Lenders need to approve enough applicants to generate revenue while minimizing default losses. This project builds a decision system to compare conservative, balanced, and growth approval strategies.

## Key Results
- Best model: Tuned XGBoost
- ROC-AUC: 0.758
- Recommended policy: Balanced
- Balanced approval rate: 74.46%
- Default rate among approved applicants: 4.36%

## Dashboard Preview

### Executive Summary
![Executive Summary](images/Executive%20Summary.png)

### Borrower Risk Profile
![Borrower Risk Profile](images/Borrower%20Risk%20Profile.png)

### Model Performance
![Model Performance](images/Model%20Performance.png)

### Approval Policy Simulator
![Approval Policy](images/Approval%20Policy.png)

## Tools Used
- Python
- pandas
- scikit-learn
- XGBoost
- Power BI
- Git/GitHub

## Repository Structure
```text
dashboard/          Power BI dashboard file
data/processed/     Cleaned and model-ready CSV outputs
images/             Dashboard screenshots
notebooks/          Data cleaning, feature engineering, modeling, and policy simulation notebook
