# Uber Taxi Demand Forecast

**Time Series Analysis Project** – Predicting Taxi Demand

This project is an introduction to **time series forecasting**, using historical taxi ride data to predict demand in different city areas. It covers classical statistical methods, machine learning, and deep learning approaches for time series prediction.

---

## 📝 Project Overview

Efficient taxi services rely on predicting demand to minimize wait times and optimize resource allocation. This project explores multiple time series forecasting techniques to predict the number of taxi orders for **77 city areas**, at **15-minute intervals** for the **next 7 days**.

---

## ⚡ Key Features

- **Time Series Methods Implemented:**  
  - Naive averages  
  - Moving averages  
  - Exponential smoothing (single, double, and triple/Holt-Winters)  
  - ARIMA and SARIMA models  

- **Machine Learning Approaches (Bonus):**  
  - Classical regression models with extracted time-based features  
  - Deep learning models (RNN/LSTM) for sequential prediction  

- **Evaluation Metric:**  
  - Mean Absolute Error (MAE)  
  - Goal: achieve **MAE ≤ 10** on the test dataset (bonus target: MAE ≤ 8)

---

## 📂 Dataset

- `taxi_pickups_area.csv`: Historical taxi rides (2019-04-01 to 2019-06-23)  
- `taxi_submission_file.csv`: Template for submission predictions  

Data is structured for **77 areas**, with timestamps in **15-minute intervals**.

---

## 🛠 Implementation

- Python 3  
- Libraries: `pandas`, `numpy`, `statsmodels`, `scikit-learn`, `tensorflow` / `pytorch` (optional)  
- Recommended environment: **Google Colab** for GPU acceleration or **Jupyter Notebook**  

**Steps:**  
1. Explore and preprocess the data.  
2. Apply different forecasting methods.  
3. Evaluate models using MAE.  
4. Save the best predictions in `taxi_submission_file.csv`.

---

## 🚀 Project Goals

- Gain hands-on experience in **time series forecasting**.  
- Understand and apply **stationarity, trend, and seasonality** concepts.  
- Compare classical statistical models with machine learning and deep learning approaches.  
- Optimize predictions to improve operational efficiency for a taxi company.

---

## 📈 Bonus Challenge

- Implement advanced machine learning and deep learning models for time series.  
- Improve prediction accuracy to achieve **MAE ≤ 8** on the test dataset.

---

## 🔗 References

- [Exponential Smoothing](https://en.wikipedia.org/wiki/Exponential_smoothing)  
- [ARIMA and SARIMA](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average)  
- [Novikov Self-Consistency Principle](https://en.wikipedia.org/wiki/Novikov_self-consistency_principle)
