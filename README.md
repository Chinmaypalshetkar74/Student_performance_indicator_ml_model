# 🎓 Student Performance Indicator - ML Web App

This project aims to predict a student's **math score** based on various demographic and academic features using Machine Learning techniques. It includes **end-to-end ML pipeline development**, **model comparison**, and **Flask web app integration** for real-time prediction.

---

## 📌 Project Objective

Build a machine learning model to:
- 🎯 Predict **Math Score** of students
- 📊 Analyze the impact of gender, parental education, lunch type, test preparation, and other factors on student performance
- 💡 Deploy a **user-friendly web interface** for live predictions

---

## 🧪 Target Variable

> **🎯 Target:** `math score`  
> The project is designed to help institutions and educators identify struggling students early based on their profile and preparation level.

---

## 🔍 Exploratory Data Analysis (EDA)

Performed comprehensive EDA using:
- 📈 **Seaborn** & **Matplotlib** for visualization
- 📊 Correlation analysis
- 🧮 Distribution plots for all numeric features
- 🎯 Category-wise analysis for test preparation, gender, and parental education impact

> Sample Insights:
- Students who completed test preparation performed better
- Reading & Writing scores are highly correlated with Math score

---

## 🛠 Tech Stack & Libraries Used

### 📦 Core Libraries
- `pandas`
- `numpy`

### 📊 Visualization
- `matplotlib`
- `seaborn`

### 🧠 Machine Learning
- `scikit-learn`
- `xgboost`
- `catboost`

### 🌐 Web Framework
- `Flask`

### 🧪 Serialization
- `pickle`
- `dill`

---

## 🧠 ML Models Applied & Compared

| Model                    | R² Score |
|--------------------------|----------|
| 🥇 **Linear Regression**     | **0.8797** |
| Ridge Regression         | 0.8806 |
| CatBoost Regressor       | 0.8516 |
| AdaBoost Regressor       | 0.8481 |
| Random Forest Regressor  | 0.8469 |
| XGBoost Regressor        | 0.8278 |
| Lasso Regression         | 0.8253 |
| KNN Regressor            | 0.7839 |
| Decision Tree Regressor  | 0.7543 |

> ✅ **Final Model Selected**: Linear Regression  
> 🔍 Reason: Best balance of accuracy, interpretability, and generalization.

---

## dataset =

