# Task 2: Customer Segmentation

This repository contains a Jupyter Notebook for customer segmentation using K-Means clustering. The notebook demonstrates the process of downloading a dataset, preprocessing it, and performing clustering to identify distinct customer segments.


Dataset
The dataset used in this notebook is the Customer Segmentation dataset from Kaggle. It can be downloaded from this link.

Steps Performed
Download and Load Dataset: The dataset is downloaded using the opendatasets library and loaded into a Pandas DataFrame.

Python
!pip install opendatasets --quiet
import opendatasets as od
od.download("https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python")
Data Preprocessing:

Dropped the CustomerID column.
Converted Gender to numeric values (Male: 1, Female: 0).
Standardized the dataset using StandardScaler.
Exploratory Data Analysis:

Plotted histograms with KDE for each feature.
Created scatter plots to visualize relationships between features.
Clustering:

Applied K-Means clustering to the standardized data.
Determined the optimal number of clusters using the Elbow Method.
Visualized the clusters and cluster centers.
Visualization:

Histograms with KDE for feature distributions.
Scatter plots for feature relationships.
K-Means clustering visualization.

## Results
Optimal Number of Clusters: 3

## Cluster Centers:

[[ 1.00919971 -1.22553537]
 [ 0.99158305  1.23950275]
 [-0.62618966 -0.01439238]]

 
## Dependencies
Python 3
Jupyter Notebook
Pandas
Matplotlib
Seaborn
NumPy
Scikit-learn
Opendatasets
Usage
To run the notebook, open Task2.ipynb in Jupyter Notebook or Google Colab.

You can view and download the notebook here.
