Dynamic Pricing Customer Churn Prediction
Overview
This project analyzes how customer churn risk changes under simulated dynamic pricing scenarios in grocery retail. Using household-level transaction and demographic data, we engineered customer behavior features, simulated price increases, and trained multiple machine learning models to predict churn risk.

The project goes beyond basic churn prediction by combining customer analytics, price sensitivity simulation, nonlinear modeling, probability calibration, and revenue trade-off analysis.

Business Problem
Dynamic pricing can increase short-term revenue, but excessive price increases may cause customers to churn. This project studies the trade-off between higher prices and customer retention by estimating when price increases begin to reduce expected revenue.

What This Project Demonstrates
Customer churn modeling
Dynamic pricing simulation
Feature engineering from transaction data
Time-based train/test splitting
Handling class imbalance
Logistic Regression baseline modeling
Random Forest modeling
XGBoost modeling
Isotonic probability calibration
Threshold optimization
Revenue trade-off analysis
To make the project more realistic, churn was not treated as a simple fixed label. Instead, price sensitivity was simulated using customer discount dependency, and model probabilities were calibrated using isotonic calibration to improve decision-making under different pricing scenarios.