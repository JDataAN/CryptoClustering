# CryptoClustering

Cryptocurrency Clustering Analysis

## Overview

This repository presents a comprehensive analysis of cryptocurrency data, employing K-Means clustering and Principal Component Analysis (PCA) to uncover underlying patterns and relationships. The primary objective is to assess the impact of dimensionality reduction on clustering results and visualize the outcomes through various plots.

## Data

The dataset used in this analysis comprises a collection of cryptocurrencies, encompassing historical price data over specified time periods. The data undergoes preprocessing and feature engineering to prepare it for clustering.

## Methodology

### Data Loading and Preprocessing:

Load the cryptocurrency data into a suitable data structure.
Perform necessary preprocessing steps, such as handling missing values and scaling the data.

## K-Means Clustering:

Apply K-Means clustering to the original dataset to identify distinct clusters.
Utilize the Elbow method to determine the optimal number of clusters.
Dimensionality Reduction with PCA:

Employ PCA to reduce the dimensionality of the data, projecting it onto a lower-dimensional subspace.
Choose an appropriate number of principal components based on explained variance.

K-Means Clustering on Reduced Data:

Repeat the K-Means clustering process on the PCA-reduced data.

## Visualization and Analysis:

* Plot Elbow curves to compare the performance of clustering on original and reduced data.
* Create scatter plots to visualize the clusters in both original and reduced feature spaces.
* Analyze the impact of dimensionality reduction on clustering accuracy and interpretability.

# Results

The analysis provides insights into the following:

* Optimal Number of Clusters: The Elbow method helps identify the optimal number of clusters for both original and PCA-reduced data.
* Clustering Performance: Comparison of clustering results reveals the effectiveness of PCA in improving clustering efficiency or maintaining similar performance.
* Visualization: Scatter plots offer a visual representation of cluster formation and the impact of dimensionality reduction.

## Dependencies

Python: The core programming language.
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Scikit-learn: For machine learning algorithms, including K-Means and PCA.
Matplotlib: For data visualization.
Seaborn: For statistical data visualization.

# License

This project is licensed under the MIT License. See the LICENSE file for more information.

