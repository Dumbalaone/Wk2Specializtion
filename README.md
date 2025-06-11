# Kenya External Debt Forecasting with ARIMA

This project uses a time series forecasting model to predict Kenya's total external debt stocks for the years 2023–2026, based on historical data from 2013 to 2022.

## 📊 Project Overview

The dataset (`Kenya.csv`) contains annual external debt indicators for Kenya. We focus specifically on the **"Total External Debt Stocks"** metric and apply an **ARIMA (AutoRegressive Integrated Moving Average)** model to forecast future values.

### Key Steps:
1. **Data Cleaning**: Removing metadata rows and formatting columns.
2. **Time Series Construction**: Structuring the data with time-based indices.
3. **Visualization**: Plotting historical data.
4. **Modeling**: Fitting an ARIMA(1,1,1) model to capture trends.
5. **Forecasting**: Predicting external debt values for 2023–2026.
6. **Visualization of Forecast**: Displaying the future projection alongside historical data.

---

## 📁 Files

- `Kenya.csv`: Source data for external debt indicators.
- `forecast_debt.py`: Python script containing all logic to clean data, build the ARIMA model, and generate forecasts.
- `README.md`: This file.

---

## 🛠️ Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pand!


[Screenshot 2025-06-12 002640](https://github.com/user-attachments/assets/e308590f-3381-44be-a52d-54a41c9dd951)
![Screenshot 2025-06-12 002434](https://github.com/user-attachments/assets/f5f634f6-8df5-4bb0-ba77-ad2e4efeca03)
as matplotlib statsmodels
