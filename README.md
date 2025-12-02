# 📈 Gold Price Time Series Analysis (2014–2024)

This project analyzes 10 years of historical gold prices (2014–2024) and builds a 1-year forecast using Meta/Facebook Prophet. The goal is to understand long-term trends, seasonal movements, and future price behavior through time-series modeling.

### 🔍 Project Overview

Performed data cleaning, preprocessing, and transformation on daily gold price data (2806 rows, 7 columns).

Conducted Exploratory Data Analysis (EDA) with trend visualization, resampling (monthly & yearly), and summary statistics.

Prepared data for modeling by renaming Prophet-compatible fields (ds, y).

Built and trained a Prophet forecasting model to capture trend + seasonality patterns.

Generated a 365-day future forecast, along with Prophet’s components (trend, yearly seasonality, changepoints).

Visualized actual vs. predicted prices using Prophet’s built-in plotting tools.

### 📊 Dataset Summary

Date Range: 2014-01-01 → 2024-11-06

Columns: Date, Price, Open, High, Low, Volume, Chg%

Price insights:

Minimum: 24,545

Maximum: 79,257

Average: ≈40,700

Median: ≈32,980

A simple trend estimate shows an upward movement of ~4,085 units per year on average.

### 🧠 Modeling Approach

Model: Prophet (additive model with trend + seasonality)

Future periods forecasted: 365 days

Outputs:

Forecasted price curve

Upper & lower uncertainty intervals

Trend and seasonal component plots

### 💡 Highlights:

Processed daily price data (2,806 rows, 7 features)

Performed exploratory analysis & resampling (monthly/yearly trends)

Renamed columns (ds, y) & prepared Prophet-ready dataset

Built a forecasting model to estimate future price movement

Plotted forecast, uncertainty intervals & seasonal components

### 📌 Key Findings

Gold price shows a strong long-term upward trend.

Seasonal effects are present, which Prophet captures automatically.

Forecast indicates continued growth with predictable seasonal fluctuations.

### 🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Prophet

Jupyter Notebook
