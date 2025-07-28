🥑 Avocado Price Forecasting with Prophet
📌 Overview
This project utilizes the Facebook Prophet library to perform time series forecasting on avocado prices in the United States. Using historical data, we analyze trends, seasonality, and predict average prices for the next 365 days.

📊 Dataset
The dataset includes the following key features:

Date: The date of the record
AveragePrice: The average price of avocados on that date
year: Extracted from the date for visual analysis
Note: The dataset is preprocessed and sorted by date before applying the model.

⚙️ Libraries Used
pandas
numpy
matplotlib
seaborn
prophet (formerly fbprophet)
🚀 Forecasting Process
Data Preprocessing

Sort dataset by date
Rename columns for Prophet compatibility (ds, y)
Exploratory Data Analysis

Line plot of price over time
Count plot of records per year
Modeling

Train Prophet model on historical data
Generate future dataframe (365 days ahead)
Predict future prices
Visualize predictions and Prophet components (trend, seasonality)
📈 Sample Output
Price Forecast Plot
Forecast

Trend & Seasonality Components
Components

🧠 Insights
Prophet successfully identifies trends and seasonal cycles in avocado pricing.
This type of analysis can help retailers, wholesalers, and economists plan better for future market conditions.
About
This project focuses on forecasting avocado prices using the Facebook Prophet time series model. The dataset contains historical average prices of avocados in the United States. By preprocessing the data and applying Prophet, we can visualize trends, seasonal effects, and make future price predictions for a one-year period.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
100.0%
Footer
© 20
