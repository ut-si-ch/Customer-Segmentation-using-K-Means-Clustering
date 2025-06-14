
## 📊 Customer Segmentation using K-Means Clustering

### 🧩 Overview

This project performs **unsupervised clustering** to segment customers based on their demographics and purchasing behavior. The goal is to enable targeted marketing by identifying distinct customer groups, using techniques like **KMeans**, **PCA**, and **t-SNE** for visualization and modeling.

---

### 💼 Business Understanding

Modern businesses thrive on personalization. One-size-fits-all marketing is expensive and often ineffective. This project tackles that by segmenting a company's customer base, helping stakeholders understand:

* Who their customers are
* How they behave
* Which groups offer the most value

Effective segmentation leads to **better-targeted campaigns**, **resource optimization**, and **increased customer retention**.

---

### 📊 Data Understanding

* **Dataset**: `marketing_campaign.csv` (Tab-separated)
* **Size**: 2,240 rows × 29 columns
* **Source**: Simulated data representing customer information like income, age, family size, product spending, and registration date.
* **Data Preprocessing**:

  * Null values handled (e.g., dropped missing `Income`)
  * Date column (`Dt_Customer`) transformed into day, month, year
  * Redundant or non-numeric features processed using encoding or removal

---

### 🤖 Modeling and Evaluation

* **Standardization**: Used `StandardScaler` for feature normalization
* **Dimensionality Reduction**:

  * **PCA** to reduce feature space
  * **t-SNE** for 2D visualization of high-dimensional clusters
* **Clustering**:

  * Applied **KMeans**
  * Used **Elbow Method** to find the optimal number of clusters
* **Evaluation**:

  * Visual validation through cluster separation
  * Interpretability of clusters using spending and demographic patterns

---

### 📌 Conclusion

* Customers were segmented into **distinct behavioral groups** (e.g., high-spending singles, budget-conscious families)
* These clusters provide actionable insights for targeted promotions, loyalty programs, and pricing strategies
* The project demonstrates practical application of unsupervised learning, from data wrangling to modeling and business interpretation

---
