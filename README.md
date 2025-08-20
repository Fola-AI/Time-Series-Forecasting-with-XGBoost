# Time Series Forecasting with XGBoost

This repository demonstrates how to build a **time series forecasting model** using [XGBoost](https://xgboost.readthedocs.io/) on hourly electricity consumption data from PJME (PJM Energy). The notebook walks through the process of exploring the data, preparing it for machine learning, and training a gradient boosting model to predict future electricity demand.

## Project Overview

- Dataset: `PJME_hourly.csv` (hourly PJM electricity demand in MW).
- Goal: Forecast future electricity load based on historical hourly demand.
- Approach:
  - Load and preprocess the time series.
  - Train/test split (training data up to 2015, test data after 2015).
  - Feature engineering from datetime (hour, day, month, etc.).
  - Train an XGBoost regressor.
  - Evaluate model performance with RMSE.


## Usage
Clone the repository:

Data/PJME_hourly.csv
Launch Jupyter Notebook:

jupyter notebook
Open and run:
PJME_Timeseries_Forecast_with_XGBoost.ipynb
Results
Visualization of electricity demand trends and seasonality.
Forecasting future hourly loads using XGBoost.
Model performance evaluated with Root Mean Squared Error (RMSE).

## Future Improvements
Hyperparameter tuning with cross-validation.
Experimenting with other ML/DL models (e.g., LightGBM, LSTMs).

Incorporating weather and external features for better accuracy.
