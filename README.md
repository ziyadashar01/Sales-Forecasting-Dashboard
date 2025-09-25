# Sales Forecasting Dashboard Project

## Overview
This project demonstrates time-series forecasting for monthly retail sales using ARIMA and Prophet. 
The goal is to predict monthly sales to inform inventory planning and staffing decisions.

## Dataset
- **Suggested Source:** public retail monthly sales data (or Kaggle retail datasets)
- Place your CSV as `data/monthly_sales.csv` with columns: `date` (YYYY-MM-DD) and `sales` (numeric).

## Steps
1. Data ingestion and resampling to monthly frequency
2. Exploratory data analysis (trend, seasonality)
3. Forecasting using ARIMA (statsmodels) and Prophet (optional)
4. Model evaluation (MAE, RMSE)
5. Dashboard visuals exported as PNG for publishing

## How to Run
1. Place your dataset in `data/monthly_sales.csv`.
2. Open `sales_forecasting.ipynb` in Jupyter and run cells.
3. If using Prophet, install with `pip install prophet` (or `pip install fbprophet` for older environments).

## Results (example)
- ARIMA MAE: ~1200
- Prophet MAE: ~1000
- Key insights: strong seasonal peaks in November-December, steady growth year-over-year.

## Tech Stack
- Python (Pandas, NumPy, Statsmodels, Prophet)
- Jupyter Notebook
- Power BI / Tableau / Looker Studio (for dashboard)
