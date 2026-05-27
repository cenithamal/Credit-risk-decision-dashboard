# Credit Risk Decision Dashboard

## Overview
A credit risk scoring and approval policy simulation project that predicts borrower default risk, segments applicants by risk, and supports lending policy decisions through a Power BI dashboard.

## Business Problem
Lenders need to approve enough applicants to generate revenue while minimizing default losses. This project builds a decision system to compare conservative, balanced, and growth approval strategies.

## Solution
The project uses borrower financial and demographic features to train a default risk model, generate probability-of-default scores, and simulate approval thresholds.

## Key Results
- Best model: Tuned XGBoost
- ROC-AUC: 0.758
- Recommended policy: Balanced
- Balanced approval rate: 74.46%
- Default rate among approved applicants: 4.36%

## Dashboard
Add screenshots here.

## Tools
Python, pandas, scikit-learn, XGBoost, Power BI, Git/GitHub

## Repository Structure
Explain notebooks, dashboard, data/processed.

## Future Improvements
Automated refresh, more borrower behavior data, probability calibration, advanced policy simulation.
