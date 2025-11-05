# 🏠 House Price Prediction using Linear Regression

## 📘 Overview
This project predicts the median house value based on various housing-related factors like the number of rooms, bedrooms, income, and location. The dataset used is from the **California Housing Dataset**.

The model uses **Linear Regression** to understand how these independent features influence the overall house price.

---

## 🧠 Problem Statement
To predict the **median house price** of a district based on features such as `median_income`, `total_rooms`, and `households`.

---

## 📊 Dataset Description
| Column Name | Description |
|--------------|-------------|
| longitude | District longitude |
| latitude | District latitude |
| housing_median_age | Median age of houses |
| total_rooms | Total number of rooms in the district |
| total_bedrooms | Total number of bedrooms |
| population | Total population |
| households | Total number of households |
| median_income | Median income of residents |
| median_house_value | Target — Median house price |
| ocean_proximity | Category showing proximity to the ocean |

---

## ⚙️ Tools & Libraries
- Python 🐍  
- Pandas, NumPy — Data preprocessing  
- Matplotlib, Seaborn — Visualization  
- Scikit-learn — Linear Regression model  

---

## 🧩 Steps in Project

### 1️⃣ Data Preprocessing
- Handle missing values in `total_bedrooms`.
- Encode `ocean_proximity` using **OneHotEncoder**.
- Normalize numerical columns.
- Split dataset (80% Train / 20% Test).

### 2️⃣ Exploratory Data Analysis
- Visualized correlation using a **heatmap**.
- Checked income vs price relationship using scatter plot.
- Analyzed feature distributions and outliers.

### 3️⃣ Model Building
- Implemented **Linear Regression** using `sklearn.linear_model.LinearRegression`.
- Trained on preprocessed data.

### 4️⃣ Model Evaluation
Metrics used:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 📈 Results
- Found **strong correlation** between `median_income` and `median_house_value`.
- Model achieved **R² ≈ 0.65**, indicating good predictive capability for a simple regression.

---

## 🚀 Future Scope
- Add **Polynomial Regression** for non-linear data.
- Try **Ridge/Lasso Regularization** to reduce overfitting.
- Build an interactive web app using **Streamlit**.

---

## 👨‍💻 Submitted By
**Umang Kaklotar**  
B.Tech Computer Engineering  
Internship Submission — Machine Learning Track
