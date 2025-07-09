# Multi-Model Clustering Analysis with Internal Evaluation

This repository presents an in-depth comparative analysis of multiple clustering algorithms applied to a multivariate dataset with 10 numerical features. The goal is to explore cluster structures using various unsupervised learning techniques and identify the best-performing model using internal evaluation metrics.


## 📊 Clustering Models Implemented

The following clustering techniques are applied:

1. **K-Means**
2. **K-Medoids** (`scikit-learn-extra`)
3. **Fuzzy C-Means** (`fcmeans`)
4. **Agglomerative Clustering**
   - Linkages: `ward`, `single`, `complete`, `average`
5. **DBSCAN**
6. **HDBSCAN**
7. **OPTICS**
8. **Gaussian Mixture Model (GMM)**
9. **Spectral Clustering**
10. **Birch Clustering**


## 📐 Evaluation Metrics Used

Each algorithm is evaluated using the following internal clustering metrics:

- **Silhouette Score**: Measures how similar each point is to its own cluster compared to other clusters.
- **Calinski-Harabasz Index**: Higher values indicate better-defined clusters.
- **Davies-Bouldin Index**: Lower values indicate better clustering structure.
- **Dunn’s Index**: (Calculated for K-Means) Higher values represent more compact and well-separated clusters.










