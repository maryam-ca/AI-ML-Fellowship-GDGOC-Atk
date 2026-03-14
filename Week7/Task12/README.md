# Week 7 – Unsupervised Learning & Market Basket Analysis

## Introduction

This notebook explores different **Unsupervised Machine Learning techniques** and applies **Association Rule Mining** to perform **Market Basket Analysis**.

Unsupervised learning is used when data does not contain labeled outputs. The goal is to find patterns, clusters, or relationships within the data.

This project includes the following topics:

- K-Means Clustering (from scratch concept)
- Hierarchical Clustering
- Dimensionality Reduction using PCA
- Data Visualization using t-SNE
- Association Rule Mining using the Apriori algorithm
- Market Basket Analysis project

All topics and the final project are implemented in **a single Jupyter Notebook**, as required in the assignment instructions.

---

# Topics Covered

## 1. K-Means Clustering

K-Means is an unsupervised learning algorithm used to group data into clusters.

The algorithm works in the following steps:

1. Select the number of clusters (K).
2. Randomly initialize centroids.
3. Assign each data point to the nearest centroid.
4. Update the centroid position.
5. Repeat the process until centroids stop changing.

In this notebook, K-Means clustering is demonstrated using a sample dataset and visualized using scatter plots.

---

## 2. Hierarchical Clustering

Hierarchical clustering builds clusters step by step by merging or splitting clusters.

There are two approaches:

- Agglomerative (bottom-up)
- Divisive (top-down)

In this project we use **Agglomerative Clustering** where:

- Each data point starts as its own cluster
- Clusters are merged gradually
- Final clusters are formed based on similarity

The clustering results are visualized using plots.

---

## 3. Principal Component Analysis (PCA)

PCA is a **dimensionality reduction technique**.

It reduces the number of features while preserving the most important information in the dataset.

Benefits of PCA:

- Reduces computation time
- Removes redundant features
- Helps visualize high dimensional data in 2D

In this notebook, PCA is used to transform the dataset into two principal components and visualize the results.

---

## 4. t-SNE Visualization

t-SNE (t-Distributed Stochastic Neighbor Embedding) is a technique used for **visualizing high-dimensional data in a lower dimension (2D or 3D)**.

It is mainly used for:

- Data visualization
- Pattern discovery
- Cluster visualization

The notebook applies t-SNE to project data into a two-dimensional space for visualization.

---

# Market Basket Analysis Project

## Introduction

Market Basket Analysis is a data mining technique used by retailers to identify relationships between products.

It helps answer questions like:

- Which products are frequently bought together?
- What items should be recommended to customers?

This technique is widely used in:

- Supermarkets
- E-commerce platforms
- Retail stores

Example:

If customers frequently buy **Bread and Butter together**, stores may place them near each other or recommend them online.

---

# Association Rule Mining

Association rule mining identifies relationships between items in transaction data.

It is based on three main metrics:

### Support
Support shows how frequently an itemset appears in the dataset.

Support = (Transactions containing item) / (Total transactions)

### Confidence
Confidence measures how often item B is purchased when item A is purchased.

Confidence = Support(A and B) / Support(A)

### Lift
Lift measures the strength of the association between two items.

Lift > 1 means the items are positively related.

---

# Apriori Algorithm

The Apriori algorithm is used to find **frequent itemsets** and generate **association rules**.

Steps of Apriori:

1. Identify frequent individual items.
2. Extend them to larger itemsets.
3. Filter itemsets based on minimum support.
4. Generate association rules.

In this project, the Apriori algorithm is implemented using the **mlxtend library**.

---

# Dataset

A simple market basket dataset is used where each row represents a transaction and each column represents a product.

Example products include:

- Milk
- Bread
- Butter
- Beer

The dataset is converted into a **binary format** where:

- 1 = Item purchased
- 0 = Item not purchased

---

# Results

Using the Apriori algorithm, the system finds:

- Frequent itemsets
- Association rules
- Confidence values
- Lift scores

These rules help identify which products are commonly purchased together.

---

# Applications of Market Basket Analysis

Market Basket Analysis is used in many real-world applications:

- Product recommendation systems
- Store layout optimization
- Cross-selling strategies
- Online recommendation engines
- Retail marketing strategies

Companies like **Amazon, Walmart, and Netflix** use similar techniques to recommend products or content.

---

# Conclusion

This project demonstrates how unsupervised learning techniques can be used to analyze and understand data patterns.

The notebook successfully covers:

- Clustering using K-Means and Hierarchical Clustering
- Dimensionality reduction using PCA
- Data visualization using t-SNE
- Association rule mining using Apriori
- Market Basket Analysis for discovering product relationships

These techniques are very useful in real-world data analysis and recommendation systems.

---

# Author

Maryam Fatima  
AI / Machine Learning Course  
Week 7 Assignment