# GermanyEnergyUsageTrends
In this notebook, I performed exploratory data analysis (EDA) and time series visualization on Germany's energy consumption dataset. The goal was to understand seasonal patterns, daily/weekly trends, and energy usage dynamics using Python's powerful plotting libraries.

## 📌 What I Did

- Loaded and parsed a time series dataset (`Germany_Energy_TimeSeries.csv`)
- Converted and set the **Date** column as a proper datetime index
- Extracted **year**, **month**, and **weekday name** for temporal analysis
- Visualized different aspects of energy usage with:
  - Line plots
  - Area plots
  - Rolling means
  - Grouped bar plots and heatmaps

## 🧰 Tools I Used

- **Pandas**: for data manipulation and datetime features
- **Matplotlib & Seaborn**: for plotting
- **NumPy**: for numerical operations

## 📄 Dataset Overview

The dataset includes:
- Daily energy consumption data
- Power sources (like wind, solar, nuclear, etc.)
- Date-wise distribution of energy usage

## 🔁 My Workflow

1. **Import Libraries**
2. **Read & Parse Dataset**
   - Convert `'Date'` column to `datetime`
   - Set `Date` as the index
3. **Feature Engineering**
   - Extract new date-based columns: `year`, `month`, `weekday`
4. **Data Visualization**
   - Plotted energy consumption trends over time
   - Explored weekday patterns and monthly seasonality
   - Used rolling averages for smoothing
   - Created heatmaps and grouped plots to detect trends

## ✅ Final Outcome

This analysis provided clear insights into how energy consumption varies:
- Across months and weekdays
- With different power sources
- Over rolling time windows

## 🎯 What’s Next?

This kind of EDA can be extended for:
- Forecasting future energy demand
- Detecting anomalies in usage patterns
- Building ML models using engineered time series features
