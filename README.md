# 🛍️ Customer Segmentation using K-Means Clustering

This project demonstrates how to perform customer segmentation using **K-Means clustering** on the **Mall Customers** dataset. The tutorial covers data exploration, preprocessing, determining the optimal number of clusters using the elbow and silhouette methods, and creative visualization of clustering results. This project is designed to provide clear teaching insights and practical techniques for unsupervised learning.

---

## 🎯 **Objective**

The goal of this project is to segment customers based on their age, annual income, and spending score. The tutorial explains:
- How to preprocess and scale customer data.
- Methods to determine the optimal number of clusters.
- How to apply K-Means clustering for customer segmentation.
- Interpretation of cluster characteristics through various visualizations.

---

## 📂 **Dataset Overview**

**Dataset:** Mall Customers  
- **Samples:** 7043  
- **Features:**  
  - `CustomerID`: Unique identifier
  - `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`
- **Target:** Not applicable (unsupervised learning)
  
After encoding and selecting key features (`Age`, `Annual Income (k$)`, and `Spending Score (1-100)`), the dataset is preprocessed and scaled for clustering.

---

## 🏗️ **Technique: K-Means Clustering**

K-Means clustering is an unsupervised learning algorithm that groups data points into **k** clusters by minimizing the variance within each cluster.  
**Key Advantages:**
- **Simplicity:** Easy to implement and interpret.
- **Efficiency:** Works well with large datasets.
- **Insightful:** Helps in discovering hidden patterns in customer behavior.

---

## 📈 **Model and Visualizations**

### **Model Process:**
1. **Data Scaling:** Features are standardized to ensure fair distance calculations.
2. **Elbow Method:** Used to determine the optimal number of clusters by plotting inertia values.
3. **Silhouette Analysis:** Validates the optimal number of clusters by computing silhouette scores.
4. **K-Means Clustering:** Segments customers into distinct clusters based on the selected features.

### **Visualizations Include:**
- **Elbow Plot:** To identify the “elbow” point indicating the optimal k.
- **Silhouette Plot:** To evaluate the quality of the clustering.
- **Scatter Plot:** Displays clusters with different colors based on Annual Income and Spending Score.
- **Radar Chart:** Visualizes the normalized cluster centers across key features.
- **Bar Chart:** Shows customer distribution per cluster.
- **3D Scatter Plot:** Interactive visualization using Plotly to show multi-dimensional cluster separation.

---

## ⚙️ **How to Run the Code**

### **1. Clone the Repository:**
```bash
git clone https://github.com/your-username/mall-customers-clustering.git
