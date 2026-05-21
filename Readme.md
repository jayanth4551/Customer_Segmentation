# Customer Segmentation using K-Means Clustering

## Overview

This project implements the K-Means Clustering algorithm to group customers of a retail store based on customer behavior.

The clustering is performed using:

* Age
* Spending Score

The model helps identify different customer groups for better business understanding and marketing strategies.

---

# Dataset

Dataset used:
Customer Segmentation Dataset from Kaggle.

Features available in the dataset:

* Customer ID
* Gender
* Age
* Annual Income
* Spending Score

Features used for clustering:

* `Age`
* `Spending Score (1-100)`

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

# Steps Performed

1. Imported required libraries
2. Loaded the dataset
3. Selected Age and Spending Score features
4. Applied the Elbow Method to determine optimal clusters
5. Trained the K-Means Clustering model
6. Predicted customer clusters
7. Visualized customer segments and centroids

---

# Algorithm Used

K-Means Clustering

K-Means groups similar data points into clusters based on distance from cluster centroids.

The clustering objective is:

J = \sum_{i=1}^{k}\sum_{x \in C_i} ||x - \mu_i||^2

Where:

* (C_i) = Cluster
* (\mu_i) = Cluster centroid
* (x) = Data point

---

# Data Visualization

Plots included:

* Elbow Method Graph
* Customer Segmentation Scatter Plot
* Cluster Centroids Visualization

---

# Conclusion

The K-Means algorithm successfully grouped customers into different clusters based on age and spending behavior. These customer segments can help businesses improve customer targeting and decision-making.

---

# Future Improvements

* Use additional customer features
* Apply feature scaling
* Try Hierarchical Clustering
* Use advanced clustering techniques

---

# Author

Jayanth4551
