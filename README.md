# Wholesale Customer Segmentation Analysis

## Overview
This project involves a comprehensive analysis of a wholesale distributor's customer data. The goal is to segment customers based on their annual spending in various product categories. The analysis includes data preprocessing, exploratory data analysis (EDA), clustering (using KMeans and Agglomerative Clustering), and Principal Component Analysis (PCA).

## Data Source
The dataset used is the 'Wholesale customers data set' from Kaggle, which includes data on customers' annual spending in diverse product categories like Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicassen.

## Installation
Ensure that you have the following Python libraries installed:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- scikit-learn

To install these, run:

!pip install pandas numpy matplotlib seaborn scipy scikit-learn

# Project

Data Download: Use Kaggle's API to download the dataset.

Data Exploration: Load and explore the dataset using Pandas.

Data Visualization: Visualize data distributions and correlations using Seaborn and Matplotlib.

Outlier Detection: Identify and remove outliers using the Interquartile Range (IQR) method.

Data Normalization: Normalize data using Min-Max Scaler for effective clustering.

Clustering Analysis: Perform KMeans and Agglomerative Clustering to segment customers.

Principal Component Analysis (PCA): Reduce dimensionality and analyze principal components.

# Results

The project identifies distinct customer segments, providing insights for targeted marketing and inventory management.

Features like Milk, Grocery, Detergents_Paper, Delicassen, and Fresh are significant in explaining the variance in the dataset.

Regional differences in purchasing patterns are evident, informing regional marketing strategies.

PCA reduces the dataset's dimensionality while retaining significant variance, aiding in analysis and modeling.

# Conclusion

This analysis offers valuable insights into the wholesale distributor's customer base, which can be utilized for informed decision-making in various business operations.
