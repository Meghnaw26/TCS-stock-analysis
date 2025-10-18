# TCS-Stock-Analysis


## Project Type: Data Analyst/ Data Science


## Project Overview
A time-series analysis of TCS (Tata Consultancy Services) stock history that includes EDA, event marking (dividends, stock splits), and predictive modeling experiments to forecast closing prices.
The goal is to analyze the historical data of TCS stock to gain insights into stock behavior, identify trends, and forecast future stock prices.


## Tools & Technologies
- Python (pandas, numpy)
- Jupyter Notebook
- Visualization: matplotlib, plotly
- Time-series / ML: scikit-learn (LinearRegression, RandomForestRegressor), xgboost


## Data Preprocessing and Feature Engineering
- Converted Date column to datetime and sorted chronologically for meaningful time-series analysis.
- Converted price-related columns (Open, High, Low, Close) to numeric types and handled any non-numeric entries.
- Extracted time features: Year, Month, Day, DayOfWeek to capture seasonality and recurring patterns.
- Created technical indicators and derived features:
  - Moving averages (SMA, EMA) to capture trend information.
  - Returns / daily returns to capture volatility.
  - Volume-related statistics to capture trading activity.
  - Marked corporate events: Dividends and Stock Splits as boolean/indicator columns.
- Cleaned and handled missing values where required.


## Predictive Modeling (what i did)
- Prepared features by dropping Close from predictors and used lagged / derived features to predict the next-period close.
- Trained and compared several regressors:
   - Linear Regression — baseline linear time-series regression.
   - Random Forest Regressor — to capture non-linear relationships.
   - XGBoost Regressor — gradient boosting model for improved performance.
- Evaluated models using MAE, RMSE and R² on the test split. (All evaluation code and printed metrics are available in the notebook.)


