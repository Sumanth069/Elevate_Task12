# Elevate_Task12
Customer segmentation using KMeans clustering on the Mall Customers dataset. Includes data preprocessing, feature scaling, elbow method for optimal K selection, cluster visualization, and business-oriented customer segment interpretation.


This project demonstrates customer segmentation using the KMeans clustering algorithm, an unsupervised machine learning technique. The goal is to group customers based on their annual income and spending behavior to help businesses make data-driven marketing decisions.

# Dataset

Primary: Mall Customer Segmentation Dataset (Kaggle)

Features Used:

Annual Income (k$)

Spending Score (1–100)

Dropped Column: CustomerID (not useful for clustering)

# Tools & Technologies

Python

Scikit-learn

Pandas

Matplotlib / Seaborn

# Project Workflow

Load and explore the dataset

Select relevant features

Apply feature scaling using StandardScaler

Use the Elbow Method to find the optimal number of clusters

Train the KMeans model

Assign cluster labels to customers

Visualize customer segments

Interpret clusters for business insights

# Results

Optimal number of clusters selected using elbow plot

Customers segmented into distinct groups based on income and spending

Cluster visualization using scatter plots

Segmented dataset saved as a CSV file

# Output

<img width="765" height="784" alt="Image" src="https://github.com/user-attachments/assets/437d5a90-e575-46b0-9d3d-e3d428976ba1" />

<img width="655" height="799" alt="Image" src="https://github.com/user-attachments/assets/a70880f6-2853-4ea4-90e5-276f7a78406b" />
