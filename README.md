🥑 Avocado Price Forecasting with Prophet
📌 Overview
This project utilizes the Facebook Prophet library to perform time series forecasting on avocado prices in the United States. By analyzing historical data, we uncover trends and seasonal patterns, and forecast the average price of avocados for the next 365 days.

📊 Dataset
The dataset includes the following key features:

Date: The date of each record

AveragePrice: The average price of avocados on that date

year: Extracted from Date for time-based analysis

✅ Note: The dataset is preprocessed and sorted by date before applying the forecasting model.

⚙️ Libraries Used
pandas

numpy

matplotlib

seaborn

prophet (formerly fbprophet)

🚀 Forecasting Process
1. Data Preprocessing
Sorted the dataset by Date

Renamed columns to fit Prophet format:

ds for date

y for target value (AveragePrice)

2. Exploratory Data Analysis
Visualized price trends using line plots

Created count plots to examine yearly data distribution

3. Modeling with Prophet
Trained Prophet on historical data

Created a future dataframe for 365 days ahead

Generated price forecasts using the trained model

Visualized:

Forecasted avocado prices

Prophet components (trend, yearly seasonality)

