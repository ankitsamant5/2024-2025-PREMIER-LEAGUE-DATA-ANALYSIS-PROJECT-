# 2024-2025-PREMIER-LEAGUE-DATA-ANALYSIS-PROJECT-
Data analytics project on Premier League 2024/25 player stats. Covers data cleaning, feature engineering, exploratory analysis, correlations, and predictive modeling (Linear, Ridge, Lasso, Elastic Net, Decision Tree, XGBoost). Objective: identify key performance drivers and predict goal contributions

## Overview

This project explores Premier League 2024/25 player statistics with the objective of understanding player performance and predicting goal contributions. Using Python, the notebook covers the full data science pipeline — from cleaning and feature engineering to exploratory analysis, correlation studies, and predictive modeling.

Contents of the Notebook

## Data Cleaning & Preparation

Handled missing values and removed incomplete records.

Renamed columns for clarity and consistency.

Dropped outliers using IQR.

Created new features: per-90 metrics, finishing ability (Goals − xG), carry/pass ratio.

## Exploratory Data Analysis (EDA)

Scatterplots and bar charts of matches, minutes, goals, and assists.

Radar charts comparing Mohamed Salah and Dane Scarlett (volume vs efficiency).

Visualizations of finishing ability and progression style.

## Correlation & Feature Insights

Heatmaps to identify key predictors of contributions.

Confirmed xG, xAG, and minutes as strongest features.

## Predictive Modeling

Linear Regression, Ridge, Lasso, Elastic Net.

Decision Tree and XGBoost for non-linear comparison.

Ridge Regression achieved the best performance (R² ≈ 0.64).

Residual analysis and actual vs predicted plots.

## Key Insights

Goal contributions scale linearly with expected stats.

Per-90 metrics uncover hidden efficient performers.

Non-linear models underperformed after outlier removal, proving the dataset is mostly linear.

## Conclusion

This project demonstrates that linear models best explain player contributions in the Premier League 2024/25 dataset. Ridge Regression proved most stable, highlighting that expected goals, expected assists, and minutes are the strongest predictors. The analysis shows that clubs and analysts should focus on per-90 efficiency alongside raw totals when evaluating talent.

## Tech Stack

Python (pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost)

Jupyter Notebook
