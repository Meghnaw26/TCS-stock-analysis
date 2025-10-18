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

<img width="898" height="488" alt="Image" src="https://github.com/user-attachments/assets/5e90a0f1-399f-48e7-8984-a9c8586cc946" />



## Exploratory Data Analysis 

<img width="923" height="527" alt="Image" src="https://github.com/user-attachments/assets/0f58966f-2c9f-4132-aad2-3519d0325a22" />



<img width="1114" height="592" alt="Image" src="https://github.com/user-attachments/assets/6dd9d190-e3db-4077-8864-8efc2b6ebb2f" />



<img width="1087" height="606" alt="Image" src="https://github.com/user-attachments/assets/c8a5d736-099b-49e8-ae92-b57ca3bb7e6b" />



<img width="905" height="648" alt="Image" src="https://github.com/user-attachments/assets/b50d3de7-e28c-4a7e-a67e-efcda5f45ec0" />



<img width="1121" height="674" alt="Image" src="https://github.com/user-attachments/assets/f615ee99-21a3-4e3a-b6ff-0b154d5c2686" />



<img width="917" height="547" alt="Image" src="https://github.com/user-attachments/assets/3ffb5b40-6e17-4d3e-85d1-7d57f05c87bb" />



<img width="1102" height="650" alt="Image" src="https://github.com/user-attachments/assets/e8682e6e-a9cc-49cc-9b56-f327e0edd9ae" />



<img width="1054" height="690" alt="Image" src="https://github.com/user-attachments/assets/74a1f81a-487e-4175-b4e8-93462e9c6c2f" />



<img width="1079" height="654" alt="Image" src="https://github.com/user-attachments/assets/d8d7be47-c6b5-4c7e-856d-022605341fa9" />



<img width="830" height="630" alt="Image" src="https://github.com/user-attachments/assets/2f954660-8982-4e56-a4b9-3b8e07668941" />



<img width="664" height="457" alt="Image" src="https://github.com/user-attachments/assets/ea4ee57a-d2ff-4bae-8a5d-1c8daf7bf807" />



<img width="861" height="575" alt="Image" src="https://github.com/user-attachments/assets/2ace434f-5542-4c01-ab94-d72581963ae9" />



<img width="1055" height="603" alt="Image" src="https://github.com/user-attachments/assets/5c41cfe1-530b-4a9e-a2b5-6d3471c6a1b1" />



<img width="853" height="605" alt="Image" src="https://github.com/user-attachments/assets/d2783b7c-35c4-4676-be34-f52024be2883" />



<img width="914" height="586" alt="Image" src="https://github.com/user-attachments/assets/8a313ee1-348a-49b6-ba90-7b2ee5c402fa" />



<img width="914" height="662" alt="Image" src="https://github.com/user-attachments/assets/f1ca2a10-a33b-4ee2-afd8-6d76aef9f080" />



<img width="844" height="538" alt="Image" src="https://github.com/user-attachments/assets/99bd4a41-a792-43d4-80cd-869962ee2763" />



<img width="841" height="659" alt="Image" src="https://github.com/user-attachments/assets/06758854-0406-468b-9170-fee2444267c6" />



<img width="780" height="561" alt="Image" src="https://github.com/user-attachments/assets/10f9124e-0fc3-44eb-9da1-356f84447528" />



<img width="1122" height="715" alt="Image" src="https://github.com/user-attachments/assets/a491b31a-4fc2-4417-bf68-4154af6718ef" />



<img width="1092" height="719" alt="Image" src="https://github.com/user-attachments/assets/4d99b8f4-47fe-4157-bf03-5ec77fb2ecc3" />



<img width="1043" height="655" alt="Image" src="https://github.com/user-attachments/assets/0507720c-50f8-418a-963f-cdd68c0797d2" />




