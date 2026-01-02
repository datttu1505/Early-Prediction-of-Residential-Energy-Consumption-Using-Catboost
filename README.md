# Household Energy Consumption Predictive Modeling

A machine learning pipeline for analyzing and predicting annual residential energy usage using the 2020 Residential Energy Consumption Survey (RECS) dataset. This project implements high-precision regression models to estimate total site energy consumption (BTUs) based on building characteristics, household demographics, and appliance usage.

## Description

This project provides a robust framework for energy load forecasting and factor analysis. It automates the ingestion of high-dimensional survey data (over 700 variables), performs feature engineering to identify key energy drivers, and benchmarks state-of-the-art gradient boosting algorithms. By utilizing Stratified K-Fold cross-validation, the tool ensures that predictive models generalize effectively across diverse housing types and climate zones.

## Key Features

- **Multi-Model Benchmarking:** Comparative analysis of CatBoost, XGBoost, and Random Forest regressors.
- **Automated Preprocessing:** Intelligent handling of categorical variables and missing data inherent in large-scale survey datasets.
- **Stratified K-Fold Validation:** Robust evaluation strategy to ensure model stability and prevent overfitting.
- **Feature Importance Profiling:** Visual identification of the primary drivers of household energy consumption (e.g., HVAC age, square footage, climate region).
- **High-Precision Forecasting:** Achieves an $R^2$ score of >0.99 using optimized CatBoost architectures.

## Use Case

Energy utility providers, urban planners, and policy analysts can use this tool to simulate how changes in building standards or appliance efficiency impact total energy demand. By inputting specific household characteristics (like insulation quality or heating system types), the model provides a data-driven estimate of expected annual BTU consumption, allowing for more accurate load balancing and targeted efficiency incentives.
