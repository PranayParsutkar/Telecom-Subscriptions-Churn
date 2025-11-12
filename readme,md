# Telecom Market Share & Churn Prediction
Major Project – EvoAstra Ventures Inc.

A full end-to-end market churn analytics system built using 15+ years of Indian telecom subscription data from TRAI.
The project covers data engineering → feature engineering → churn modeling → explainability → insights → business impact.

## Project Overview
This project builds a complete and auditable telecom churn prediction pipeline, focusing on understanding market dynamics, customer churn behavior, and operator competitiveness across India.

## Goals
Build a reproducible churn analytics pipeline
Achieve >85% model accuracy and ROC-AUC >0.85
Use ML models such as Random Forest, XGBoost, LightGBM, CatBoost & ANN
Visualize churn trends and operator performance
Provide actionable, ROI-driven business insights
Deliver dashboard-ready metrics for operational teams

## Dataset Details
Source: Telecom Regulatory Authority of India (TRAI)
Volume: ~70,728 records (25MB+)
Timeline: 2009 – 2025
Coverage:
42 operators
38 telecom circles
Wireless + Wireline
Monthly-level granularity
Includes market evolution across 2G, 3G, 4G, 5G.

## Data Cleaning & Preprocessing
Removed/Imputed missing values
Converted year & value columns to numeric
Cleaned non-numeric characters
Standardized categorical fields
Split datasets: Wireless vs Wireline
Extracted top 10 providers for visualization
Created date column for time-series analysis

## Feature Engineering
Created advanced telecom features including:
Temporal Features
lag_1, lag_3, lag_6 subscriber changes
month, year decomposition
Market Dynamics
Market Share
Market Rank
Churn Severity
Herfindahl–Hirschman Index (HHI)
Volatility & Stability Indicators
Categorical/Geographical Features
Metro vs Non-Metro classification
Operator geographic diversity
Wireless/Wireline binary encoding

## Exploratory Data Analysis – Key Insights
BSNL & Airtel were historically dominant until Jio's disruptive entry in 2016
2011 saw the largest number of provider shutdowns (2G spectrum scam)
Market consolidation from 20+ operators → 3 national players (Jio, Airtel, BSNL)
Non-metro circles contribute significantly higher subscribers
High-churn circles: Jharkhand, Bihar, Maharashtra
28% of operator–circle combinations fall under high churn risk

## Machine Learning Models
Models Used:
Random Forest
XGBoost
LightGBM
CatBoost
Artificial Neural Network (ANN)
Time-Series Split Cross Validation

## Top Model Performance
Model	       Accuracy   F1-Score	  ROC-AUC
LightGBM        0.9721	  0.9251	  0.9767
Random Forest	0.9679	  0.9158	  0.9685
XGBoost	        0.9675    0.9135	  0.9755
CatBoost	    0.9673	  0.9160	  0.9708
ANN	            0.8988	  0.8080	  0.9171

LightGBM is the best model overall.

## Model Explainability (SHAP)
Top predictive features:
value_lag_1 (most important)
value
type_of_connection
is_wireless
market_rank
market_share
operator_geographic_diversity
Low-impact features:
month, year, circle_type

## Visualizations
The project includes charts for:
Year-over-Year operator growth
Circle-wise churn patterns
Operator market rank evolution
Wireless vs Wireline comparison
HHI competition index
Metro vs Non-Metro subscribers
Model ROC & Precision-Recall Curves
Churn Category distribution

## Business Impact
The churn system supports:
Identifying high-risk churn regions
Optimizing retention campaigns
Strategic market expansion
Understanding subscriber behavior shifts
Reducing revenue leakage
Monitoring operator competitiveness

## Final Performance:
97%+ prediction accuracy
~0.98 ROC-AUC
Pipeline ready for real-world dashboard deployment