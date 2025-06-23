# Unsupervised Wine Quality Clustering

This project applies unsupervised learning to the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) to explore patterns in physicochemical properties and identify natural groupings of wine samples.

## Problem Statement
The goal is to use clustering techniques to segment wines based on chemical features, potentially revealing quality-related groupings and aiding in quality control without labeled data.

## Methods Used
- Exploratory Data Analysis (EDA)
- Feature Scaling
- K-Means Clustering
- DBSCAN Clustering
- Silhouette Score Evaluation
- PCA for Visualization

## Results
- Optimal clusters identified using elbow method and silhouette score.
- DBSCAN also evaluated for density-based clustering.
- Clustering results visualized in 2D using PCA.

## Files Included
- `Unsupervised_Wine_Quality_Clustering.ipynb`: The main notebook
- `winequality-red.csv`: Dataset used

## Dataset Source
[UCI Machine Learning Repository – Wine Quality](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
