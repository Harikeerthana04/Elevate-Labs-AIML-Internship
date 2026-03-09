# 🧠 Task 8: K-Means Clustering - Mall Customer Segmentation

This task is part of an AI & ML Internship project focused on applying unsupervised learning using **K-Means Clustering**. The goal is to segment mall customers into distinct groups based on their spending patterns and income.

---

## 📌 Objective

To implement **K-Means Clustering** on the Mall Customer dataset and determine optimal clusters using the **Elbow Method** and **Silhouette Score**, and then visualize the customer segments.

---

## 📊 Dataset

**Mall_Customers.csv**  
- Columns used:  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`

Download Source: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## 🧪 Tools & Libraries Used

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Steps Performed

1. **Loaded and explored the dataset**  
2. **Selected relevant features** (`Annual Income`, `Spending Score`)  
3. **Visualized the dataset** in 2D
4. **Applied Elbow Method** to determine optimal number of clusters (K)
5. **Trained KMeans model** on selected features  
6. **Predicted cluster labels** and added to the dataset  
7. **Visualized the clusters and centroids**
8. **Evaluated clusters using Silhouette Score**

---

## 📈 Elbow Method Result

The Elbow Method plot showed a clear "elbow" at **K = 5**, suggesting that 5 clusters are optimal.

---

## 📌 Final Results

- **Optimal Clusters (K):** 5
- **Silhouette Score:** _e.g._ `0.55` (value may vary slightly)
- **Cluster Plot:**

![Cluster Plot](screenshots/cluster_plot.png)

---

## Screenshots/cluster_plot

![image](https://github.com/user-attachments/assets/c5281684-e621-4814-a185-8f1ba5a639e3)
![image](https://github.com/user-attachments/assets/25dee35c-bb0e-4a3c-98f1-8f90c361a0a4)
![image](https://github.com/user-attachments/assets/e8860eb1-6e10-40b6-af27-ea479c1089dd)

---

## 📂 Project Structure

Task-8-KMeans-Clustering/
│
├── Mall_Customers.csv
├── notebook.ipynb
├── screenshots/
│ └── cluster_plot.png
├── README.md

