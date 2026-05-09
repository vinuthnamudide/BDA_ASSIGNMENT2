# 📊 Big Data Analytics Assignment using PySpark

## 📌 Overview

This project demonstrates the implementation of three core data analytics techniques using **PySpark**:

* ✅ Classification (Logistic Regression)
* ✅ Clustering (K-Means)
* ✅ Recommendation System (ALS Algorithm)

All models are implemented and executed in **Google Colab** using real-world datasets.

---

## 🚀 Technologies Used

* Python 🐍
* PySpark ⚡
* Google Colab ☁️
* Matplotlib 📈
* Pandas 🧮

---

## 📂 Datasets Used

### 1️⃣ Classification

* **Dataset Name:** Iris Dataset
* **Source:** Seaborn Repository
* **Link:** https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv
* **Features:**

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
* **Target:** Species

---

### 2️⃣ Clustering

* **Dataset Name:** Mall Customers Dataset
* **Source:** Customer Segmentation Dataset
* **Link:** https://raw.githubusercontent.com/vjchoudhary7/customer_segmentation_tutorial/master/Mall_Customers.csv
* **Features:**

  * Age
  * Annual Income (k$)
  * Spending Score (1–100)

---

### 3️⃣ Recommendation System

* **Dataset Name:** Goodbooks-10k Dataset
* **Source:** Goodreads Dataset
* **Link:** https://raw.githubusercontent.com/zygmuntz/goodbooks-10k/master/ratings.csv
* **Features:**

  * User ID
  * Book ID
  * Rating

---

## ⚙️ Implementation Details

### 🔹 1. Classification (Logistic Regression)

* Data preprocessing using VectorAssembler
* Label encoding using StringIndexer
* Train-test split (80:20)

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1 Score

**Visualization:**

* Confusion Matrix
* Feature Scatter Plot

---

### 🔹 2. Clustering (K-Means)

* Feature transformation using VectorAssembler
* K-Means clustering (k = 3)

**Evaluation Metric:**

* Silhouette Score

**Visualization:**

* Cluster Scatter Plot
* Elbow Method Graph

---

### 🔹 3. Recommendation System (ALS)

* Collaborative Filtering using ALS Algorithm
* Train-test split

**Evaluation Metric:**

* RMSE (Root Mean Square Error)

**Output:**

* Top 5 recommendations per user

**Visualization:**

* Actual vs Predicted Ratings
* Rating Distribution

---

## 📊 Results

* ✔ Classification achieved good accuracy on Iris dataset
* ✔ Clustering grouped customers into meaningful segments
* ✔ Recommendation system successfully predicted user preferences

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Install PySpark (if not installed)
3. Run all cells step-by-step
4. Upload dataset manually (for Mall Customers if needed)

---

## 📁 Project Structure

```
📦 BDA-Assignment
 ┣ 📜 BDA_ASSIGNMENT.ipynb
 ┣ 📜 README.md
 ┗ 📂 datasets (optional)
```

---

## 🎯 Learning Outcomes

* Understanding of PySpark MLlib
* Hands-on with Big Data tools
* Implementation of ML algorithms on distributed systems

---

## 📌 Conclusion

This project provides a complete pipeline for performing **classification, clustering, and recommendation** using PySpark, demonstrating practical knowledge of Big Data Analytics.

---

## 👨‍💻 Author

* Name: M Vinuthna
* Roll No:160123771311
* Course: Big Data Analytics
* Institution: Chaitanya Bharathi Institute of Technology
---
