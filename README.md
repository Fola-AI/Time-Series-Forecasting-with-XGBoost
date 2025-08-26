# PJME Time Series Forecasting with XGBoost

This project demonstrates a machine learning approach to time series forecasting of regional electricity demand using XGBoost. The dataset contains hourly power consumption (in Megawatts) for the PJM East (PJME) region in the United States, and the goal is to build an accurate predictive model that can capture seasonal patterns and forecast future electricity usage.

**🔍 Project Overview**

Objective: Forecast future PJME energy demand using historical data.

Techniques Used:

Time series feature engineering (lag features, rolling statistics, date-time decomposition).

Gradient boosting with XGBoost for supervised regression.

Model evaluation using Root Mean Squared Error (RMSE) and visual diagnostics.

Outcome: The project demonstrates how traditional time series data can be reframed into a supervised learning problem and modeled effectively with gradient boosting methods.

**📂 Project Structure**

PJME_Timeseries_Forecast_with_XGBoost.ipynb: Main notebook containing data preprocessing, feature engineering, modeling, and results.

**Sections covered:**

Data loading and exploration

Feature engineering (time-based and lag features)

Train-test split respecting temporal order

Model training with XGBoost

Forecasting and evaluation

**🛠️ Tools & Libraries**

Python

Pandas / NumPy – data manipulation

Matplotlib / Seaborn – data visualization

Scikit-learn – preprocessing, evaluation metrics

XGBoost – machine learning model

**📊 Results & Insights**

The model successfully captured daily and seasonal electricity consumption trends.

Feature engineering with lag values and rolling statistics improved forecasting accuracy.

XGBoost proved effective for handling large-scale time series with non-linear patterns.

**🚀 Key Learning Points**

Converting time series data into a supervised learning problem can unlock powerful ML methods.

Feature engineering plays a critical role in improving predictive performance.

Gradient boosting (XGBoost) is highly adaptable and performs well in real-world forecasting tasks.

**🔮 Future Improvements**

Hyperparameter tuning with grid/random search for optimal performance.

Incorporation of external covariates (e.g., temperature, holidays, weather).

Comparison with other forecasting methods (Prophet, LSTM, ARIMA).
