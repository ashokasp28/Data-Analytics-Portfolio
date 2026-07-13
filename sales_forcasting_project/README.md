# Sales Forecasting using Machine Learning

## 📌 Project Overview

This project predicts daily store sales using historical sales data from Rossmann stores. It demonstrates the complete machine learning workflow including data cleaning, exploratory data analysis, feature engineering, model building, and evaluation.

---

## 🎯 Objective

Develop a machine learning model capable of forecasting daily sales accurately.

---

## 📂 Dataset

Rossmann Store Sales Dataset

Dataset contains information including:

- Store ID
- Sales
- Customers
- Promotions
- Holidays
- Store Type
- Competition Distance
- Date

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis

---

## 🤖 Machine Learning Models

- Linear Regression
- Random Forest Regressor

---

## 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|-------|------:|------:|------:|
| Linear Regression | 940.94 | 1391.96 | 0.869 |
| Random Forest Regressor | 263.41 | 439.48 | 0.987 |

---

## 📌 Key Insights

- Customer count is the strongest predictor of sales.
- Promotions positively impact sales.
- Store Type influences sales performance.
- Seasonal trends significantly affect sales.
- Random Forest outperformed Linear Regression across all evaluation metrics.

---

## 📚 Future Improvements

- Time-series forecasting models
- Hyperparameter tuning
- Cross-validation
- XGBoost Regressor
