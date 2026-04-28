# Inflation-Prediction-ML-Model

## Overview

This project explores the use of machine learning techniques to forecast inflation using macroeconomic time-series data. The goal is to assess whether standard regression models can capture inflation dynamics from economic indicators.

---

## Problem Statement

Inflation forecasting is important for economic planning, monetary policy, and financial decision-making. This project investigates whether machine learning models can predict inflation using available macroeconomic variables and how they compare to simple baseline approaches.

---

## Dataset

* Macroeconomic indicators across multiple countries
* Includes inflation and related economic variables
* Data preprocessing involved handling missing values and aligning time-series observations

---

## Methodology

* Data cleaning and preprocessing using `pandas` and `NumPy`
* Feature selection from macroeconomic indicators
* Train-test split for model evaluation
* Regression model implemented using `scikit-learn`
* Performance evaluated using MSE and R²

---

## Model Performance

* Mean Squared Error (MSE): 1.95
* R² Score: -0.72
* Compared against a naive baseline (mean prediction)

**Insight:** The model underperformed the baseline, highlighting the difficulty of predicting inflation using limited linear features and the non-stationary nature of macroeconomic data.

---

## Key Insights

* Inflation data exhibits strong noise and non-stationarity
* Feature selection significantly impacts predictive performance
* Simple regression models may not capture macroeconomic complexity
* Baseline comparison is essential for evaluating real predictive value

---

## Tech Stack

* Python
* pandas, NumPy
* scikit-learn
* matplotlib (for visualisation)

---

## Future Improvements

* Incorporate time-series models (ARIMA, LSTM)
* Add more macroeconomic indicators
* Improve feature engineering and stationarity handling
* Compare with ensemble models (Random Forest, XGBoost)
