# Customer Segmentation Using K-Means

## 📌 Project Overview

Customer segmentation is a key marketing strategy used to divide customers into distinct groups based on their behavior and characteristics. In this project, we apply **K-Means clustering**, an unsupervised machine learning algorithm, to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**.

The goal is to identify meaningful customer groups and suggest suitable **marketing strategies** for each segment.

---

## 🎯 Objectives

* Load and prepare a customer dataset
* Clean and preprocess the data
* Scale numerical features
* Determine the optimal number of clusters using the **Elbow Method**
* Apply **K-Means clustering**
* Visualize customer segments
* Profile each cluster and derive marketing actions
* Save the final clustered dataset

---

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization
* **Scikit-learn** – machine learning (K-Means, scaling)

---

## 📂 Dataset Description

The dataset used is a **Mall Customers dataset**, containing the following columns:

| Column Name            | Description                       |
| ---------------------- | --------------------------------- |
| CustomerID             | Unique customer identifier        |
| Gender                 | Male / Female                     |
| Age                    | Age of the customer               |
| Annual Income (k$)     | Annual income in thousand dollars |
| Spending Score (1-100) | Spending behavior score           |

The dataset is stored as **Mall_Customers.csv**.

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Load the CSV file using Pandas

### 2️⃣ Data Cleaning

* Remove unnecessary columns (CustomerID)
* Encode categorical data (Gender)
* Check for missing values

### 3️⃣ Feature Scaling

* Standardize numerical features using **StandardScaler**
* Required because K-Means is distance-based

### 4️⃣ Elbow Method

* Compute WCSS (Within-Cluster Sum of Squares)
* Identify optimal number of clusters (k = 5)

### 5️⃣ K-Means Clustering

* Apply K-Means with selected k
* Assign cluster labels to each customer

### 6️⃣ Visualization

* Plot clusters using Income vs Spending Score

### 7️⃣ Cluster Profiling

* Analyze average Age, Income, and Spending Score per cluster
* Interpret customer behavior

---

## 📊 Customer Segments & Marketing Strategies

### 🟢 Cluster 0 – Low Income, Low Spending

* Price-sensitive customers
* **Strategy:** Discounts, basic offers, loyalty points

### 🔵 Cluster 1 – High Income, Low Spending

* Careful or conservative buyers
* **Strategy:** Personalized campaigns, premium awareness

### 🟡 Cluster 2 – Young, High Spending

* Trend-focused customers
* **Strategy:** Influencer marketing, flash sales

### 🔴 Cluster 3 – High Income, High Spending (VIP)

* Most valuable customers
* **Strategy:** Exclusive deals, VIP membership, premium services

### 🟣 Cluster 4 – Low Income, High Spending

* Impulsive or lifestyle-driven buyers
* **Strategy:** EMI options, affordable trendy products

---

## 📁 Output Files

* **Mall_Customers.csv** – Raw dataset
* **Customer_Segmentation_Output.csv** – Dataset with cluster labels
* **Visualizations** – Elbow curve and cluster plots

---

## ✅ Conclusion

This project demonstrates how **unsupervised machine learning** can be used to understand customer behavior and improve marketing decisions. K-Means clustering effectively groups customers into actionable segments, helping businesses increase engagement and revenue.

---

## 🚀 Future Enhancements

* Apply PCA for dimensionality reduction
* Try other clustering algorithms (Hierarchical, DBSCAN)
* Build an interactive dashboard using Power BI or Tableau
* Deploy as a web application

---

## 👤 Author

**Sujith**
Customer Segmentation Project
Machine Learning Mini Project
