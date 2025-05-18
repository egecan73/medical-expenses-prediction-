# 🩺 Medical Expenses Prediction

This project aims to predict annual medical expenses for individuals based on their demographic and behavioral characteristics using regression models. The dataset includes simulated insurance data from the U.S.

---

## 📊 Objective

To help insurance providers estimate healthcare costs more accurately and enable risk-based premium pricing by building an interpretable and performant regression model.

---

## 🗂️ Dataset Overview

- **Source:** Simulated dataset from the book *Machine Learning with R* (Lantz, 2013)
- **Observations:** 1,338 individuals
- **Target variable:** `charges` – total annual medical expenses
- **Features:**
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`

---

## 🧪 Methods Used

- Exploratory Data Analysis (EDA)
- Feature encoding (One-Hot Encoding)
- Regression modeling:
  - Linear Regression
  - Random Forest Regressor
- Model evaluation with MAE, RMSE, R²
- Feature importance analysis

---

## ⚙️ Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## ✅ Key Results

| Model            | MAE     | RMSE    | R² Score |
|------------------|---------|---------|----------|
| Linear Regression| 4181.19 | 5796.28 | 0.784    |
| Random Forest     | **2554.38** | **4581.11** | **0.865** |

- **Smoking status**, **age**, and **BMI** were the most impactful features.
- Random Forest captured non-linear relationships more effectively.

---

## 🔮 Future Improvements

- Try XGBoost or Gradient Boosting
- Hyperparameter tuning (GridSearchCV)
- Deploy via Flask API or Streamlit

---

## 📁 How to Use

1. Clone the repository  
