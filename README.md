# 🌍 Life Expectancy Analysis and Prediction

This project analyzes global life expectancy trends and builds predictive models to understand how various socio-economic and health factors influence life expectancy across countries.

---

## 🧠 Business Problem

Governments and health organizations need reliable insights to:
- Improve public health outcomes
- Allocate healthcare budgets more effectively
- Identify key factors affecting life expectancy in different regions

This project aims to **analyze global patterns** and **predict life expectancy** using machine learning models.

---

## ✅ Proposed Solution

- Perform **exploratory data analysis (EDA)** to uncover trends, correlations, and anomalies.
- Build predictive models to estimate **life expectancy** based on variables such as:
  - GDP
  - Immunization rates
  - Infant mortality
  - Healthcare expenditure
  - Education

---

## 📂 Dataset Overview

- **Source:** [Kaggle - WHO Life Expectancy Data](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- **Records:** 2,930+
- **Countries:** 190+
- **Years:** 2000–2015
- **Target Variable:** `Life expectancy`

### 🧾 Features Include:
- Status (Developed/Developing)
- Adult mortality
- Alcohol consumption
- BMI
- HIV/AIDS prevalence
- GDP
- Schooling
- Hepatitis B immunization
- Healthcare expenditure

---

## 🔧 Data Preprocessing

- Handled missing values with imputation
- Converted categorical features (e.g., `Status`) to numeric
- Scaled numerical features using Min-Max scaling
- Checked multicollinearity using heatmaps and correlation matrices
- Split data into training and test sets

---

## 📈 Models Used

| Model                | RMSE  | MAE   | R² Score |
|---------------------|-------|-------|----------|
| **Linear Regression**       | 2.48  | 1.89  | 0.90     |
| Random Forest Regressor    | 1.92  | 1.47  | 0.94     |
| Gradient Boosting Regressor| 1.85  | 1.39  | 0.95     |

📌 **Best Performing Model:** Gradient Boosting Regressor

---

## 📊 Visual Insights

- Correlation heatmap of features
- Life expectancy over time by region
- Top contributing factors to high and low life expectancy
- Feature importance plots (Random Forest, XGBoost)

---

## 💡 Key Findings

- **Schooling** and **Income (GDP)** positively impact life expectancy
- **Infant mortality**, **HIV/AIDS**, and **adult mortality** are strong negative predictors
- **Developed countries** show higher life expectancy with lower variance

---

## 🚀 Future Improvements

- Incorporate time series analysis for better trend modeling
- Introduce clustering to group similar countries
- Add more recent data (post-2015), possibly including COVID-19 impact
- Explore policy recommendations with explainable AI (e.g., SHAP values)

---

