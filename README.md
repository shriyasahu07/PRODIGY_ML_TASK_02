# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment retail customers based on their purchase behavior. It helps identify distinct customer groups for targeted marketing strategies using **Annual Income** and **Spending Score**.

## 📂 Dataset

- **Source**: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **File**: `Mall_Customers.csv`
- **Features Used**:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## 🧠 Objective

To identify groups of customers with similar purchasing habits using unsupervised machine learning (K-Means), and allow user interaction through a **Streamlit-based web application**.

## 🧪 Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📈 Clustering Approach

1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Standardize the numeric features.

2. **K-Means Clustering**:
   - Use the **Elbow Method** to find the optimal number of clusters.
   - Apply `KMeans` with selected features.

3. **Visualization**:
   - Plot customer segments on a 2D plane using Annual Income vs. Spending Score.

