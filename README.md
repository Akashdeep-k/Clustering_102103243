# Clustering Assignment - 102103243

This repository contains the code for an assignment on clustering techniques applied to the Wholesale Dataset. Different clustering algorithms, preprocessing techniques, and evaluation parameters were explored in this assignment.

## Clustering Techniques:

- **K-Means Clustering:** An unsupervised clustering algorithm aiming to partition data into K clusters.
- **Hierarchical Clustering:** Builds a tree of clusters where each node is a cluster consisting of one or more data points.
- **Mean Shift Clustering:** A non-parametric clustering technique aiming to discover dense regions in data.

## Evaluation Parameters:

- **Silhouette Score:** Measures the quality of clusters.
- **Calinski-Harabasz Index:** Measures cluster separation and compactness.
- **Davies-Bouldin Index:** Evaluates cluster dispersion.

## Preprocessing Techniques:

- **None:** No preprocessing applied.
- **Normalization:** Scaling each feature to a range.
- **PCA (Principal Component Analysis):** Technique for dimensionality reduction.
- **Transform:** Transforming features using specific transformations.
- **PCA + Transform (PCA+T):** Combining PCA with feature transformation.
- **PCA + Transform + Normalization (PCA+T+N):** Combining PCA, feature transformation, and normalization.

## Instructions:

1. **Installation:** Clone this repository to your local machine.

    ```bash
    git clone https://github.com/Akashdeep-k/Clustering_102103243.git
    ```

2. **Usage:** Open and run the provided Jupyter Notebook (`clustering-and-preprocessing.ipynb`). Execute the clustering algorithms by running the appropriate cells for each technique and parameter combination.

3. **Evaluation:** Analyze the results obtained for each clustering technique and preprocessing combination.