# 🥑 Avocado Price Forecasting with Prophet

## 📌 Overview

This project utilizes the **Facebook Prophet** library to perform time series forecasting on avocado prices in the United States.  
By analyzing historical data, we uncover **trends**, **seasonality**, and predict average prices for the next **365 days**.

---

## 📊 Dataset

The dataset includes the following key features:

- **Date**: The date of each record  
- **AveragePrice**: The average price of avocados on that date  
- **year**: Extracted from the date for time-based analysis  

> ✅ **Note:** The dataset is preprocessed and sorted by date before applying the forecasting model.

---

## ⚙️ Libraries Used

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `prophet` (formerly `fbprophet`)

---

## 🚀 Forecasting Process

### 1. Data Preprocessing
- Sorted the dataset by date
- Renamed columns to Prophet's expected format:
  - `ds` for the date column  
  - `y` for the target variable (average price)

### 2. Exploratory Data Analysis
- Line plot of average price over time
- Count plot of records per year

### 3. Modeling with Prophet
- Trained the Prophet model on historical data
- Created a future dataframe (365 days ahead)
- Predicted future prices
- Visualized:
  - Forecast plot
  - Trend and seasonality components

---

## 🧠 Insights

- Prophet successfully identifies **trends** and **seasonal cycles** in avocado pricing.
- This forecasting can support:
  - Retailers in pricing decisions
  - Wholesalers in supply planning
  - Economists in market behavior analysis

---


