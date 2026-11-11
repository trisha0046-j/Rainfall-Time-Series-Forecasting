# 🌧️ Rainfall Time Series Forecasting

## 📌 Project Overview
This project focuses on analyzing historical monthly rainfall data and developing forecasting models using Machine Learning and Time Series Analysis techniques.

The objective is to understand rainfall patterns and predict:
- Monthly Total Rainfall
- Maximum Daily Rainfall

## 🎯 Project Objectives
- Perform Exploratory Data Analysis (EDA).
- Identify rainfall trends and seasonal patterns.
- Perform time-series analysis and stationarity testing.
- Apply feature engineering and data preprocessing.
- Train and evaluate multiple forecasting models.
- Compare model performance using MAE and RMSE.

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## 📂 Project Structure

```text
Rainfall-Time-Series-Forecasting/
│
├── data/
│   ├── rainfall-monthly-total.csv
│   ├── rainfall-monthly-highest-daily-total.csv
│   └── rainfall-monthly-number-of-rain-days.csv
│
├── Rainfall_Time_Series.ipynb
├── total_rainfall_sarima.pkl
├── max_rainfall_linear_regression.pkl
├── max_rainfall_scaler.pkl
├── README.md
└── requirements.txt
```

## 🔍 Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Time Series Analysis
5. Stationarity Testing using ADF Test
6. Feature Engineering
7. Time-Based Train-Test Split
8. Model Training
9. Model Evaluation
10. Actual vs Predicted Visualization
11. Model Saving

## 🤖 Models Implemented

Four models were trained and evaluated:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- SARIMA

## 📊 Model Performance

### 1. Monthly Total Rainfall

| Model | MAE | RMSE |
|---|---:|---:|
| SARIMA | 71.36 | 89.49 |
| Linear Regression | 75.25 |
