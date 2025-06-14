
# Customer Segmentation using K-Means Clustering

## 🧾 Overview

This project applies **K-Means Clustering**, an unsupervised machine learning technique, to perform **customer segmentation**. Clustering allows businesses to identify distinct groups within their customer base based on behavioral and demographic data, enabling more personalized marketing and better strategic decisions.

---

## 🧠 Business Understanding

Businesses often lack labeled data but want to extract meaningful insights from existing customer information. **Customer segmentation** helps:
- Personalize marketing campaigns
- Improve product recommendations
- Allocate budget more effectively
- Understand customer needs

K-Means clustering allows automatic grouping of customers into clusters based on similar traits.

---

## 📊 Data Understanding

The dataset includes key customer attributes such as:
- Annual Income
- Spending Score
- Age
- Gender (optionally encoded)

These features provide a behavioral profile of customers that K-Means can use for segmentation.

### Preprocessing:
- Handling missing/null values (if any)
- Feature scaling using StandardScaler
- Visual exploration via pair plots, scatter plots

---

## 🤖 Modelling & Evaluation

### K-Means Clustering:
- Optimal number of clusters determined using:
  - **Elbow Method**
  - **Silhouette Score**
- Clustering performed with Scikit-learn’s `KMeans` model
- Cluster assignments added back to the original dataset

### Evaluation:
- Visual representation using 2D scatter plots
- Cluster centroids plotted
- Silhouette analysis used to validate separation
- Business interpretation of each cluster (e.g., high spenders, low income)

---

## 📌 Conclusion

- K-Means successfully segments customers into meaningful groups
- Elbow and silhouette methods are critical for choosing `k`
- Visualizations clearly show cluster boundaries and densities
- Enables businesses to take targeted actions for each segment

---

## ✅ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---
