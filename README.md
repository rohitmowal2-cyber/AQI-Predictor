# 🌫️ Air Quality Index (AQI) Predictor — Indian Cities

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-Regression-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📌 Problem Statement

Air pollution is one of the most critical environmental challenges in Indian cities like Delhi, Jaipur, and Mumbai. This project predicts the **Air Quality Index (AQI)** of Indian cities based on pollutant concentration levels using Machine Learning regression models — enabling better environmental monitoring and pollution control.

---

## 📊 Dataset

- **Source:** [Kaggle — Air Quality Data in India](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
- **File:** `city_day.csv`
- **Records:** 29,531 daily readings
- **Cities:** 26 major Indian cities
- **Features:** PM2.5, PM10, NO₂, CO, SO₂, O₃, and more
- **Target Variable:** `AQI`

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Data visualization |
| Scikit-learn | ML models & evaluation |
| XGBoost | Best performing model |

---

## ⚙️ Approach

1. **Exploratory Data Analysis (EDA)** — AQI distribution, city-wise trends, seasonal patterns
2. **Preprocessing** — Median imputation for missing values, label encoding, log transformation
3. **Model Training** — Trained 6 regression models
4. **Evaluation** — Compared using RMSE, MAE, and R² Score

---

## 📈 Model Results

| Model | RMSE | MAE | R² Score |
|-------|------|-----|----------|
| Linear Regression | 68.4 | 42.1 | 0.71 |
| Ridge Regression | 67.9 | 41.8 | 0.72 |
| Random Forest | 38.2 | 22.6 | 0.91 |
| Gradient Boosting | 35.1 | 20.3 | 0.93 |
| **XGBoost ✅ Best** | **31.4** | **18.7** | **0.95** |

---

## 📂 Project Structure
