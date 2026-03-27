# 📈 Time Series Analysis and Forecasting for Multiple Humidity Sensors in a Warehouse

## Overview

This project focuses on **time series analysis and forecasting of humidity levels** collected from **multiple sensors deployed across a warehouse environment**.  
Accurate humidity monitoring and forecasting are critical to ensure **product quality, equipment protection, and operational efficiency**, especially in industrial storage facilities.

The project demonstrates how historical sensor data can be transformed into **actionable insights** using statistical analysis, visualization, and predictive modeling techniques.

---

## 🎯 Objectives

- Analyze historical humidity data from multiple sensors
- Detect patterns, trends, and seasonality in warehouse humidity
- Compare humidity behavior across different sensor locations
- Build and evaluate forecasting models for future humidity levels
- Provide early warning insights for abnormal or risky humidity conditions

---

## 🏭 Use Case

Warehouses storing **sensitive goods** (e.g. food products, raw materials, electronics) require controlled humidity levels to prevent:

- Product spoilage or degradation  
- Equipment corrosion or malfunction  
- Regulatory non-compliance  
- Increased maintenance costs  

This project helps stakeholders **anticipate humidity changes** and supports **data-driven decision making** for environmental control systems.

---

## 📊 Dataset Description

The dataset consists of time-stamped humidity readings collected from multiple sensors installed across different warehouse zones.

**Key attributes include:**

- `timestamp` — Date and time of measurement  
- `sensor_id` — Unique identifier for each humidity sensor  
- `humidity (%)` — Relative humidity reading  
- `location` *(optional)* — Zone or area of the warehouse  

> Data is assumed to be collected at a fixed interval (e.g. every 5, 10, or 15 minutes).

---

## 🔍 Key Analysis Performed

### 1. Exploratory Data Analysis (EDA)
- Time series visualization for each sensor
- Summary statistics and data distribution
- Missing value detection
- Sensor-to-sensor comparison

### 2. Time Series Decomposition
- Trend extraction
- Seasonal pattern identification
- Residual (noise) analysis

### 3. Correlation Analysis
- Cross-correlation between sensors
- Detection of shared environmental patterns
- Identification of anomalous sensor behavior

---

## 🤖 Forecasting Techniques

The following time series forecasting approaches are explored:

- **Baseline Models**
  - Moving Average
  - Naïve Forecast

- **Statistical Models**
  - ARIMA / SARIMA
  - Seasonal decomposition-based forecasting

- **Machine Learning (optional / extendable)**
  - Regression-based forecasting
  - LSTM / RNN (for advanced implementation)

---

## ✅ Model Evaluation Metrics

Forecasting models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Visual comparison of actual vs predicted values

---

## 🧠 Insights & Findings

- Humidity shows **clear daily and weekly seasonality**
- Sensors in similar zones exhibit **high correlation**
- Certain locations experience **higher volatility**, indicating airflow or insulation issues
- Forecasting models can reliably predict short-term humidity trends

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – data manipulation  
- **NumPy** – numerical computing  
- **Matplotlib / Seaborn** – data visualization  
- **Statsmodels** – time series modeling  
- **Scikit-learn** – evaluation and ML utilities  

---
