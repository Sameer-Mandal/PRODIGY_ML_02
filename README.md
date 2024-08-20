# PRODIGY_ML_02
Task 2 of Machine learning internship at Prodigy Infotech 

Creating a K-means clustering algorithm to group customers of a retail store based on their purchase history.

The notebook outlines a K-means clustering analysis applied to customer data from a retail store, aiming to segment customers based on their purchase history. 

# Overview
This project implements a K-means clustering algorithm to group customers of a retail store based on their purchase history. The primary goal is to identify distinct customer segments that can be targeted with tailored marketing strategies.

# Methodology

1. *Importing Libraries*:
   - Essential Python libraries such as `numpy`, `pandas`, `matplotlib`, `seaborn`, and `plotly` were imported for data processing, visualization, and clustering.

2. *Data Exploration*:
   - The dataset is explored to understand the distribution of variables such as `Age`, `Gender`, `Annual Income`, and `Spending Score`.
   - Initial insights are derived from summary statistics and data visualizations.

3. *Data Visualization*:
   - Visualizations include histograms, scatter plots, and pair plots to identify potential relationships between the variables and to inform the clustering process.

4. *K-Means Clustering*:
   - The K-means algorithm is applied to segment customers into clusters based on their `Age`, `Annual Income`, and `Spending Score`.
   - The optimal number of clusters is determined using the Elbow method, which analyzes the variance explained by each cluster.

5. *Cluster Analysis*:
   - After clustering, each group is analyzed to understand the characteristics of the customers within each cluster.
   - The clusters are visualized in 2D and 3D to provide insights into how the customers are grouped.

6. *Insights*:
   - The clustering process reveals distinct customer segments, such as high-income, high-spending customers, and low-income, low-spending customers.
   - These insights can guide marketing strategies, product placements, and customer relationship management.

# *Conclusion*
The analysis successfully segments customers into meaningful clusters, providing valuable insights that can be leveraged to enhance customer engagement and improve business strategies.
