# Customer Segmentation

This project performs customer segmentation using **K-Means Clustering** on the Mall Customers dataset.

## Project Overview

The goal is to divide customers into different groups based on their:

* Age
* Annual Income
* Spending Score

## Method Used

* Data cleaning and basic checks
* Feature selection
* Feature scaling using StandardScaler
* Elbow Method to select the number of clusters
* K-Means Clustering
* Cluster visualization
* Cluster profiling
* Marketing recommendations

The Elbow Method was used to select **K = 6** clusters.

## Files

* `main.py` — Machine learning code
* `Mall_Customers.csv` — Dataset
* `customer_segments.csv` — Dataset with cluster labels
* `segment_report.txt` — Short report of each customer segment

## Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn

## Result

The model divided customers into **6 segments** with different age, income, and spending patterns. These segments can be used to create targeted marketing strategies.
Author
Eman Fatima


