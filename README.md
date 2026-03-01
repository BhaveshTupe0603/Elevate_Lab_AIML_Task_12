# 🛍️ Task 12: KMeans Customer Segmentation

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange?logo=scikit-learn)

## 📖 Overview
**Task 12** introduces **Unsupervised Learning**. Unlike previous tasks where we predicted a known target (Supervised), here we used **KMeans Clustering** to find hidden groups within customer data.

## ⚙️ Workflow
1.  **Data Loading:** Loaded Mall Customers data.
2.  **Preprocessing:** Selected `Income` and `Spending Score` and applied **StandardScaler** (crucial for distance-based clustering).
3.  **Optimization:** Used the **Elbow Method** to determine that `K=5` was the optimal number of clusters.
4.  **Modeling:** Trained KMeans and assigned cluster labels to each customer.
5.  **Visualization:** Plotted the segments to interpret business value.

## 📊 Key Segments Identified
* **VIPs:** High Income, High Spending.
* **Savers:** High Income, Low Spending.
* **Standard:** Average Income, Average Spending.

## 🖼️ Deliverables
| Elbow Plot | Cluster Visualization |
| :---: | :---: |
| <img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/e3dd738d-05fc-4b43-9827-2daa9585a175" />| <img width="850" height="701" alt="image" src="https://github.com/user-attachments/assets/36171f65-b0c8-4f1c-b916-398ed3b1aec2" />|

## 📂 Files
* [📓 Jupyter Notebook](./Task12_KMeans.ipynb)
