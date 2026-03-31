# Head and Neck Cancer Mortality Prediction

ML-based mortality prediction in head and neck cancer patients using SEER registry data.

## Overview
Developed and compared machine learning models to predict mortality risk in head and neck cancer using the SEER population-based registry (209,851 patients, 2010–2021).

## Tools & Technologies
Python · MySQL · XGBoost · Random Forest · Scikit-learn · Pandas · NumPy · Seaborn · Matplotlib · Plotly · UMAP

## Key Results
- XGBoost ROC-AUC: 0.7847
- Random Forest ROC-AUC: 0.7814
- Dataset: 198,940 records · 16 clinical features

## Methods
- Data cleaning and preprocessing in MySQL and Python
- Chi-square tests and Cramér's V correlation analysis for feature selection
- UMAP dimensionality reduction
- Stratified 5-fold cross-validation
- One-hot encoding of categorical clinical variables

## Associated With
Indiana University Indianapolis 
INFO-B521 Health Informatics
