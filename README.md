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
ARI-Prediction-Jakarta/
│
├── README.md
│
├── R/
│   ├── Analysis Code.Rmd
│
├── figures/
│   │
│   ├── eda/
│   │   ├── air-quality-distribution.png
│   │   ├── daily-distribution-variable-2.png
│   │   ├── monthly-distribution-variable-1.png
│   │   ├── distribution-air-pollution-daily.png
│   │   ├── distribution-air-pollution-monthly.png
│   │   ├── distribution-air-quality-categories.png
│   │   ├── distribution-pm2.5.png
│   │   ├── dist-aricases-airquality-monthly.png
│   │   ├── dist-pm2.5-airquality-daily.png
│   │   ├── dist-pm2.5-airquality-monthly.png
│   │   ├── trend-monthly-ari-cases.png
│   │   ├── daily-trend-pm2.5.png
│   │   ├── boxplot-co.png
│   │   ├── boxplot-no2.png
│   │   ├── boxplot-o3.png
│   │   ├── boxplot-pm10.png
│   │   ├── boxplot-pm10-visualization.png
│   │   ├── boxplot-pm2.5.png
│   │   ├── boxplot-so2.png
│   │   ├── relationship-pm10-ari-cases-monthly.png
│   │   └── relationship-pm2.5-ari-cases-monthly.png
│   │
│   ├── correlation/
│   │   ├── corr-matrix-dataset-daily.png
│   │   ├── corr-matrix-dataset-monthly.png
│   │   ├── pearson-corr-1-1.png
│   │   ├── pearson-corr-2-1.png
│   │   └── pearson-corr-3-1.png
│   │
│   ├── transformation/
│   │   └── boxcox-variable-CO.png
│   │
│   ├── pca/
│   │   ├── pca-all-variables-1.png
│   │   ├── pca-all-variables-2.png
│   │   ├── pca-all-variables-3.png
│   │   ├── pca-visualization-and-caseispa-1.png
│   │   ├── pca-visualization-and-caseispa-2.png
│   │   └── pca-visualization-and-caseispa-3.png
│   │
│   ├── gam/
│   │   ├── gam-final-1.png
│   │   ├── gam-final-2.png
│   │   └── plot-actual-prediction-gam-1.png
│   │
│   ├── arimax/
│   │   └── arimax-final-1.png
│   │
│   ├── svr/
│   │   ├── svr-importance-1.png
│   │   ├── svr-permutation-importance.png
│   │   └── plot-actual-prediction-svr-1.png
│   │
│   ├── xgboost/
│   │   ├── xgb-importance-1.png
│   │   └── xgboost-feature-importance-1.png
│   │
│   └── environmental/
│       ├── prop-airpollution-category-humidity-category.png
│       ├── prop-airpollution-category-ispu-daily.png
│       ├── prop-airpollution-rainfallcategory-daily.png
│       └── relationship-humidity-pm2.5-daily.png
│
├── results/
│   ├── predictor-screening/
│   ├── GAM/
│   ├── ARIMAX/
│   ├── SVR/
│   ├── XGBoost/
│   └── model-comparison/
│
└── index.html

## Results
AAA

## Code Availability Statement
The R code and supplementary analysis used in this study are available at the following repository: [(https://jusijin.github.io/ARI-prediction-jakarta/)]

## Team Members

- Nico Handoko
- Annisa Meta Nadjwa

## Author

**Nico Handoko**

**LinkedIn:**
https://www.linkedin.com/in/nico-handoko

**GitHub:**
https://github.com/Jusijin
