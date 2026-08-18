# Predicting Acute Respiratory Infection Cases in Jakarta Based on Air Quality and Meteorological Using Statistical and Machine Learning Models

## Overview
Acute Respiratory Infection (ARI) is one of the most common public health problems influenced by environmental factors, including air quality and meteorological factors.

## Objective
The main objective of this study is to compare the performance of statistical and machine learning models for predicting monthly ARI cases using air quality and meteorological variables.

## Dataset
The dataset consist of 59 monthly observations from January 2021 to November 2025. The variables include:

**Air Quality**
- PM2.5
- PM10
- SO2
- CO
- O3
- NO2

**Meteorological**
- Temperature (TEMP)
- Humidity (HUM)
- Rainfall (RAIN)
- Wind Speed (WSPM)
- Cloud Cover (CC)
- Atmospheric Pressure (PRES)

**Temporal**
- Trend
- Season
- ispa_lag1

The data were obtained from relevant public data sources in Jakarta.

## Data Pre-Processing
The pre-processing workflow included:
- Data cleaning and missing value handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Pearson Correlation Analysis
- Multicollinearity Assessment using Variance Inflation Factor (VIF)
- Z-score Standardization
- Chronological train-test Splitting

## Statistical and Machine Learning Models
Four models were developed and compared:
1. Generalized Additive Model (GAM)
2. Autoregressive Integrated Moving Average with Exogenous Variables (ARIMAX)
3. Extreme Gradient Boosting (XGBoost)
4. Support Vector Regression (SVR)

Feature selection and model tuning were performed according to the requirements of each modeling approach.

## Model Evaluation
Model performance was evaluated using:
- Root Mean Square Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)
- Coefficient of Determination (R²)

Lower RMSE, MAE, and MAPE values indicate lower prediction errors, while a higher R² indicates better model fit.

## Repository Structure
```text
ARI-Prediction-Jakarta/
│
├── R/
│   ├── Analysis-Code.Rmd
│
├── figures/
│   ├── eda/
│   ├── correlation/
│   ├── transformation/
│   ├── pca/
│   ├── gam/
│   ├── arimax/
│   ├── svr/
│   ├── xgboost/
│   └── environmental/
│
├── results/
│   ├── predictor-screening/
│   ├── GAM/
│   ├── ARIMAX/
│   ├── SVR/
│   ├── XGBoost/
│   └── model-comparison/
│
├── README.md
└── index.html
```

## Results
AAA

## Code Availability Statement
The R code and supplementary analysis used in this study are available at the following repository: [https://jusijin.github.io/ARI-prediction-jakarta/]

## Team Members

- Nico Handoko
- Annisa Meta Nadjwa

## Author

**Nico Handoko**

**LinkedIn:**
https://www.linkedin.com/in/nico-handoko

**GitHub:**
https://github.com/Jusijin
