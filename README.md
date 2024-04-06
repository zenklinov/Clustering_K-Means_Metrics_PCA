# K-Means Clustering: Comparing Metrics with PCA

This repository contains a Jupyter Notebook (`K-Means-comparing-metrics-with-pca.ipynb`) that demonstrates the process of performing K-Means clustering on the Iris dataset using different distance metrics (Euclidean, Manhattan, Cosine) and evaluating the clustering results with Principal Component Analysis (PCA).

## Content

### 1. Importing Dataset (Iris)

The analysis starts with importing the Iris dataset using the `load_iris()` function from scikit-learn. Information about the dataset including feature names, target names, and data shape is displayed.

### 2. Performing K-Means Clustering

K-Means clustering is performed using scikit-learn's `KMeans` class with 3 clusters. The cluster centers and labels are obtained.

### 3. Computing Distances

Euclidean, Manhattan, and Cosine distances between data points and cluster centers are computed using scikit-learn's `euclidean_distances`, `manhattan_distances`, and `cosine_distances` functions.

### 4. Dimensionality Reduction with PCA

Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset to 2 components.

### 5. Visualization of Clustering Results

Scatter plots are created to visualize the clustering results along with the distances using PCA. Each subplot represents a different distance metric (Euclidean, Manhattan, Cosine) with corresponding silhouette score displayed in the title.

### 6. Analysis of Inter-Data Distance

An analysis is provided based on the scatter plots and silhouette scores for each distance metric. The correlation between distance metrics and principal component 1 is discussed, along with insights into clustering quality.

### 7. Conclusion

The conclusion summarizes the findings of the analysis, including the assessment of clustering quality for each distance metric and recommendations for further analysis.

## Usage

To run the notebook locally, clone the repository and open the `K-Means-comparing-metrics-with-pca.ipynb` file in Jupyter Notebook or JupyterLab.

## Dependencies

- scikit-learn
- matplotlib

## Author

[zenklinov](https://github.com/zenklinov/)
