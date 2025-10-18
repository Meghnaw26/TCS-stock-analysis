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




## **Dashboard**
<img width="1905" height="999" alt="Image" src="https://github.com/user-attachments/assets/86d611fc-f3ab-4ed2-a17c-12475bea53aa" />



<img width="1910" height="996" alt="Image" src="https://github.com/user-attachments/assets/7c10047f-d538-4a2f-ae64-e102b6b21a34" />

🔗 [View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/TCSStockAnalysisDashboard/Story1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)



## Key Insights
1.	Steady Growth:
The stock price has experienced a remarkable upward trend from 2003 to 2021, reflecting strong growth in TCS's stock performance. This is evident from the candlestick chart, where prices show significant rises post-2015.


2.	Dividend Growth:
TCS has consistently increased its dividend payouts, aligning with its strong stock performance. The dashboard shows the historical relationship between dividends and closing prices, indicating healthy returns for investors.


3.	Stock Splits Impact:
Stock splits have occurred over the years, especially around periods of significant growth. This is highlighted in the timeline showing stock price changes alongside stock split events.


4.	Price vs. Volume Insights:
The close price has shown a strong positive correlation with trading volume, especially during periods of rapid price increases. The "Close Price vs Volume" chart shows how trading volume spikes during price jumps, indicating strong market interest during key events.


5.	Monthly Trading Activity:
The volume by month analysis reveals peak trading activity in certain months (e.g., April, October). This suggests seasonal trends or company-specific announcements that drive trading volume .


7.	Risk and Volatility:
The risk and volatility analysis within the dashboard can assist investors in identifying periods of higher risk, which can guide investment decisions. By tracking metrics such as daily returns and moving averages, users can assess potential price fluctuations.



## Recommendations
1.	Leverage Predictive Analytics:
Given the high accuracy of predictive models, users should rely on these forecasts for short-term price predictions. These models can be further improved with more data or more advanced techniques like ensemble models.


2.	Monitor Technical Indicators:
Continuously track technical indicators like moving averages for better trading decisions. The "MA Crossover Signals" feature can be particularly useful for detecting buying or selling opportunities based on price movements.


3.	Focus on Dividend Stocks:
Given TCS's consistent dividend growth, it would be advisable for long-term investors to consider dividend reinvestment strategies. The dashboard provides a historical view of dividends, which can help in identifying trends and predicting future payouts 


4.	Investors Should Watch for Volatility:
The stock has demonstrated periods of high volatility, especially around major growth events (stock splits and strong price rises). It's important to monitor these fluctuations, especially during market corrections, and adapt investment strategies accordingly 


5.	Consider Real-Time Data Integration:
As the current setup primarily relies on historical data, integrating real-time market data feeds would enhance the relevance and utility of the analysis. This could further improve decision-making for active traders .


6.	Risk Mitigation:
Risk assessment tools such as volatility tracking, risk-adjusted returns  and stop-loss strategies could be added to further assist investors in managing potential downsides .








