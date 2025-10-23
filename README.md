# 🚖 Taxi Demand Forecasting

## 📘 Project Overview
This project focuses on **forecasting taxi demand** across multiple city areas using **time series analysis** and **machine learning** methods.  
By predicting the number of taxi orders for each 15-minute interval over the next week, the model helps optimize fleet distribution, reduce passenger wait times, and improve operational efficiency.

---

## 🧠 Objectives
- Explore **time series forecasting techniques**: Naive averages, Moving averages, Exponential smoothing, ARIMA, and SARIMA.  
- Compare statistical models with **machine learning** and **deep learning** approaches (e.g., Random Forest, LSTM).  
- Achieve an average **Mean Absolute Error (MAE)** of ≤ 10.0 (target), or ≤ 8.0 (bonus).

---

## 📊 Dataset
**Files:**
- `taxi_pickups_area.csv` — historical taxi ride data (2019-04-01 → 2019-06-23)  
- `taxi_submission_file.csv` — template for predictions  

**Details:**
- 77 city areas  
- Data recorded every **15 minutes**  
- Goal: Forecast demand for **673 future intervals** (7 days × 24h × 4 intervals/hour)

---

## ⚙️ Methods Implemented
| Category | Techniques |
|-----------|-------------|
| **Baseline** | Naive average, Moving average |
| **Statistical** | Exponential Smoothing (Simple, Double, Triple), ARIMA, SARIMA |
| **Machine Learning** | Linear Regression, Random Forest, XGBoost |
| **Deep Learning** | RNN, LSTM, GRU for sequence modeling |

---

## 🧮 Evaluation Metric
**Mean Absolute Error (MAE)**  
\[
MAE = \frac{1}{n} \sum |y_{true} - y_{pred}|
\]

---

## 🗂️ Project Structure
```
taxi-demand-forecasting/
│
├── data/
│ ├── taxi_pickups_area.csv
│ └── taxi_submission_file.csv
│
├── notebooks/
│ ├── 01_naive_moving_average.ipynb
│ ├── 02_exponential_smoothing.ipynb
│ ├── 03_sarima_model.ipynb
│ ├── 04_machine_learning.ipynb
│ └── 05_deep_learning.ipynb
│
├── submission/
│ └── taxi_submission_file.csv
│
└── README.md
```


---

## 📈 Results
| Model | MAE (Validation) |
|--------|------------------|
| Naive Average | — |
| Moving Average | — |
| Exponential Smoothing | — |
| SARIMA | — |
| LSTM | — |

---

## 🧩 Future Work
<!-- - Integrate external features (weather, holidays, events).   -->
<!-- - Compare performance of Prophet and hybrid models.   -->
<!-- - Deploy forecasting API for real-time prediction. -->