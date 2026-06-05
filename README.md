# Customer Segmentation and Product Recommendation System

## Overview

This project applies Machine Learning techniques to segment customers based on their annual income and spending behavior. Using K-Means Clustering, customers are grouped into meaningful categories that help businesses design targeted marketing strategies and personalized product recommendations.

The project demonstrates a real-world business application of unsupervised learning and recommendation systems commonly used by e-commerce platforms and retail organizations.

---

## Objectives

* Perform customer segmentation using K-Means Clustering.
* Identify customer groups based on income and spending patterns.
* Visualize customer clusters.
* Build a simple recommendation engine based on customer segments.
* Generate business insights from the discovered segments.

---

## Dataset

### Mall Customers Dataset

Source:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Features

| Feature                | Description                       |
| ---------------------- | --------------------------------- |
| CustomerID             | Unique customer identifier        |
| Gender                 | Customer gender                   |
| Age                    | Customer age                      |
| Annual Income (k$)     | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score  |

Dataset Size:

* 200 Records
* 5 Features

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Methodology

### 1. Data Exploration

* Missing value analysis
* Statistical summary
* Data visualization

### 2. Feature Selection

Selected Features:

* Annual Income (k$)
* Spending Score (1-100)

### 3. Clustering

Applied:

* K-Means Clustering

Used the Elbow Method to determine the optimal number of clusters.

Optimal Clusters:

K = 5

### 4. Recommendation System

Generated customer-specific recommendations based on identified segments.

---

## Results

### Customer Segments Identified

1. Premium Customers
2. Careful Customers
3. Target Customers
4. Low Value Customers
5. Average Customers

### Model Evaluation

Silhouette Score:

0.554

This score indicates good cluster separation and meaningful segmentation.

---

## Business Recommendations

| Segment             | Recommendation                            |
| ------------------- | ----------------------------------------- |
| Premium Customers   | Luxury products and exclusive offers      |
| Careful Customers   | Cashback and personalized discounts       |
| Target Customers    | Trending products and promotional bundles |
| Low Value Customers | Budget-friendly products                  |
| Average Customers   | Loyalty programs and popular products     |

---

## Future Improvements

* Implement DBSCAN and Hierarchical Clustering.
* Use real e-commerce transaction data.
* Develop collaborative filtering recommendation systems.
* Deploy using Streamlit.
* Build real-time customer segmentation dashboards.

---

## Author

Anish Mahapatra

