# 🧩 Customer Segmentation using K-Means Clustering

## 📘 Overview
This project applies **K-Means Clustering** to group mall customers into different segments based on their **Annual Income**, **Spending Score**, and **Age**.

The objective is to help businesses understand customer behavior and target specific segments for better marketing and strategy.

---

## 🧠 Problem Statement
To segment mall customers into meaningful clusters using **unsupervised learning**, based on their income, spending habits, and age.

---

## 📊 Dataset Description
| Column Name | Description |
|--------------|-------------|
| Age | Age of the customer |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1–100) | Score assigned by the mall based on spending behavior |

---

## ⚙️ Tools & Libraries
- Python 🐍  
- Pandas, NumPy — Data preprocessing  
- Matplotlib, Seaborn — Visualization  
- Scikit-learn — K-Means Clustering  

---

## 🧩 Project Workflow

### 1️⃣ Data Preprocessing
- Checked for missing values.
- Selected relevant features: `Age`, `Annual Income (k$)`, `Spending Score (1–100)`.
- Standardized the data for better clustering results.

### 2️⃣ Finding Optimal Clusters
- Used **Elbow Method** to find the optimal value of *k*.
- Found **k = 5** as the best number of clusters.

### 3️⃣ K-Means Model
- Applied **KMeans** from `sklearn.cluster`.
- Fitted the model and assigned cluster labels to each customer.

### 4️⃣ Visualization
- Plotted clusters using scatter plots with distinct colors.
- Each cluster represents a different customer segment.

---

## 📈 Results
| Cluster | Annual Income (k$) | Spending Score | Age |
|----------|--------------------|----------------|-----|
| 0 | 87.00 | 18.63 | 40.39 |
| 1 | 86.53 | 82.12 | 32.69 |
| 2 | 44.15 | 49.82 | 40.32 |

- Cluster 0: High-income, low-spending customers (Potential targets).  
- Cluster 1: High-income, high-spending (Ideal customers).  
- Cluster 2: Average income and spending (Balanced group).

---

## 📊 Visual Output
- **Scatter Plot** of clusters based on Annual Income vs Spending Score.
- **Age vs Spending** to understand demographic trends.

---

## 🚀 Future Scope
- Use **Hierarchical Clustering** for comparison.
- Add more features like gender, occupation, region.
- Build a **dashboard in Streamlit or Power BI** for visualization.

---

## 🧠 Key Learnings
- Practical use of **unsupervised learning** for business applications.
- Importance of data scaling and cluster analysis.
- Insights into consumer behavior patterns.

---

## 👨‍💻 Submitted By
**Umang Kaklotar**  
B.Tech Computer Engineering  
Internship Submission — Machine Learning Track 

