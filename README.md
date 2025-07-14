# ML-Assignment-5-Clustering-Techniques
DSML Assignments
Clustering Techniques on Iris Dataset
Project Description
This repository demonstrates two fundamental clustering techniques - K-Means and Hierarchical clustering - applied to the classic Iris dataset. The implementation includes data preprocessing, clustering algorithm application, and visualization of results.

Key Features
Data Preprocessing: Standardization of the Iris dataset features

K-Means Clustering: Implementation with elbow method for optimal cluster determination

Hierarchical Clustering: Implementation with dendrogram visualization

Comparative Analysis: Side-by-side evaluation of both clustering approaches

Algorithms Implemented
1. K-Means Clustering
Description:
A centroid-based algorithm that partitions data into K clusters by minimizing within-cluster variance.

Key Steps:

Randomly initialize K centroids

Assign points to nearest centroid

Recalculate centroids as cluster means

Repeat until convergence

Visualization:

Elbow method plot for optimal K selection

Cluster visualization with centroids marked

2. Hierarchical Clustering
Description:
A tree-based approach that builds clusters either bottom-up (agglomerative) or top-down (divisive).

Key Steps:

Treat each point as its own cluster

Merge closest clusters iteratively

Build dendrogram to visualize hierarchy

Visualization:

Dendrogram showing cluster relationships

Final cluster visualization

Requirements
Python 3.x

Libraries:

NumPy

Pandas

scikit-learn

SciPy

Matplotlib

Seaborn

Usage
Clone the repository

Install required packages: pip install -r requirements.txt

Run the Jupyter notebook or Python script

Results
The implementation demonstrates:

Effective clustering of Iris dataset features

Comparison of K-Means vs Hierarchical approaches

Visualization of cluster boundaries and relationships
