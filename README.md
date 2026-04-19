# 🚀 PRODIGY_ML_TASK02  
## 📊 Customer Segmentation using K-Means Clustering

---

## ✨ Overview
This project performs **Customer Segmentation** using the **K-Means Clustering algorithm**.  
It groups customers based on **Annual Income** and **Spending Score**, helping businesses understand customer behavior and improve targeting strategies.

The **Elbow Method** is used to determine the optimal number of clusters.

---

## 🎯 Objective
To segment customers into meaningful groups for:
- Better marketing strategies  
- Customer behavior analysis  
- Business decision making  

---

## 📂 Dataset
- 📌 Source: Kaggle (Mall Customers Dataset)  
- 📊 Features used:
  - Annual Income (k$)
  - Spending Score (1–100)

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas 📊  
- Matplotlib 📈  
- Scikit-learn 🤖  

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Loading
Load and inspect dataset using Pandas.

### 2️⃣ Feature Selection
Select relevant features:
- Annual Income
- Spending Score

### 3️⃣ Elbow Method
Used to find optimal number of clusters (K).

### 4️⃣ K-Means Clustering
Train model and assign customers to clusters.

### 5️⃣ Visualization
Plot clusters and centroids for interpretation.

---

## 📉 Elbow Method Insight
The Elbow Method helps identify the best K value by plotting WCSS vs K.

👉 The “elbow point” = optimal clusters

---

## 📊 Results
Customers are segmented into:

- 💰 High Income – High Spending (Premium customers)
- 💰 High Income – Low Spending (Careful spenders)
- 💸 Low Income – High Spending (Target buyers)
- 💸 Low Income – Low Spending (Low priority)

---

## 📸 Output Preview
- Elbow graph 📉  
- Cluster visualization 📊  
- Centroids (black points) ⚫  

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas matplotlib scikit-learn
