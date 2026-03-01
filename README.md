# Costumer-Classification-with-HDBSCAN
Finding different costumer groups using HDBSCAN based on synthetic data. 

## Project Overview
This project explores **Unsupervised Learning** techniques to identify patterns and clusters within a synthetic dataset. 

The primary focus is on **HDBSCAN** (Hierarchical Density-Based Spatial Clustering of Applications with Noise). We compare its performance and methodology against the traditional **K-Means** algorithm, specifically highlighting HDBSCAN's ability to handle noise and clusters of varying densities and shapes.

## Workflow

The `HDBSCAN.ipynb` notebook follows this pipeline:

1.  **Data Preprocessing:** * Scaling features using `StandardScaler` (crucial for distance-based algorithms).
2.  **Visualization:**
    * Using `KernelDensity` estimation to understand data distribution.
    * **3D Plotting:** Visualizing clusters in three dimensions using `mpl_toolkits.mplot3d`.
3.  **Model Training:**
    * Fitting `KMeans` with a predefined number of clusters.
    * Fitting `hdbscan.HDBSCAN` to find natural clusters and outliers.
4.  **Comparison:**
    * Visual comparison of cluster assignments between K-Means and HDBSCAN.
    * Quantitative scoring using `adjusted_rand_score`.

## Requirements
See requirements.txt
