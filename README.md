# 🌍 Air Quality Forecasting using Time Series Analysis

> **An end-to-end Time Series Forecasting project completed as part of an IIT Time Series Analysis assignment, focused on predicting the next 48 hours of air pollutant concentrations using statistical and machine learning forecasting techniques.**

---

# 📌 Project Overview

Air pollution has become a significant environmental and public health concern worldwide. Accurate forecasting of air quality enables governments, environmental agencies, and researchers to issue timely warnings and make informed decisions.

This project develops an end-to-end forecasting pipeline using historical air quality sensor data to predict the next **48 hours** of multiple air quality variables. Two forecasting approaches—**SARIMA** and **Prophet**—were implemented and compared based on their forecasting performance using **Root Mean Squared Error (RMSE)**.

---

# 🎯 Objective

The objective of this project is to:

* Forecast air quality measurements for the next **48 hours**
* Compare multiple time series forecasting models
* Evaluate model performance using RMSE
* Export prediction results in the required submission format
* Build a complete forecasting workflow from preprocessing to model evaluation

---

# 📁 Project Structure

```text
time-series-air-quality-forecasting/
│
├── data/
│   └── AirQualityUCI_clean.csv
│
├──docs/
│    └── Problem_Statement.pdf
│
├── notebooks/
│   └── air_quality_forecasting.ipynb
│
├── outputs/
│   ├── air_quality_48hr_forecast_submission.xlsx
│   └── air_quality_48hr_forecast_submission_prophet.xlsx
│   
└──  README.md

```

---

# 🔄 Project Workflow

```
Raw Dataset
    ↓
Data Cleaning
    ↓
Missing Value Treatment
    ↓
Datetime Parsing
    ↓
Exploratory Data Analysis (EDA)
    ↓
Stationarity Testing
    ↓
Feature Engineering
    ↓
SARIMA Model
    ↓
Prophet Model
    ↓
Model Comparison
    ↓
RMSE Evaluation
    ↓
48-Hour Forecast Generation
    ↓
Excel Submission Export
```

---

# 📊 Exploratory Data Analysis

The dataset was explored to understand:

* Missing values
* Data distribution
* Seasonal patterns
* Trends
* Sensor relationships
* Correlation between variables
* Time series visualization

---

# ⚙️ Data Preprocessing

The preprocessing pipeline included:

* Handling missing values
* Datetime conversion
* Index creation
* Cleaning invalid observations
* Sorting chronological records
* Preparing data for forecasting models

---

# 🤖 Forecasting Models

## 1. SARIMA

Seasonal AutoRegressive Integrated Moving Average (SARIMA) was used to capture trend and seasonal behavior within the air quality data.

### Advantages

* Captures seasonality
* Works well for structured time series
* Produces stable forecasts

---

## 2. Prophet

Meta's Prophet forecasting model was also implemented for comparison.

### Advantages

* Automatic trend detection
* Handles seasonality effectively
* Robust against missing observations

---

# 📈 Model Evaluation

Both forecasting models were evaluated using:

**Root Mean Squared Error (RMSE)**

The final model was selected based on lower forecasting error across the required air quality variables.

---

# 📌 Results

* Successfully generated **48-hour forecasts**
* Compared SARIMA and Prophet models
* Evaluated forecasting performance using RMSE
* Exported prediction results into Excel submission format
* Built a reusable forecasting workflow

---

# 👩‍💻 Author

**Diyaa Choudhary**

Aspiring Business Risk Analyst | SQL | Advance Excel | Tableau | Python | Time Series Analysis

---
## If you found this project helpful, feel free to ⭐ the repository!
