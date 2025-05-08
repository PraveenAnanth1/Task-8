# Task 8: Clustering with K-Means

## Objective

Perform unsupervised learning using K-Means clustering to segment data. The task includes:

* Visualizing the data (with optional PCA reduction to 2D)
* Finding the optimal number of clusters using the Elbow Method
* Assigning cluster labels
* Evaluating clustering performance using the Silhouette Score

---

## Tools and Libraries

* **Scikit-learn** for clustering, PCA, and evaluation
* **Pandas** for data handling
* **Matplotlib** for visualization
* **NumPy** for numerical operations

---

## Dataset

* **Mall Customer Segmentation Dataset** (Loaded from an online CSV URL)

---

## Steps

1. **Load and Preprocess Data**

   * Load the dataset using Pandas.
   * Select relevant features (e.g., `Annual Income (k$)` and `Spending Score (1-100)`).
   * Standardize the features.

2. **Optimal Cluster Determination**

   * Apply the Elbow Method by plotting the inertia values for different numbers of clusters.

3. **Fit K-Means**

   * Choose an optimal `k` (e.g., `k=5` based on the elbow method).
   * Fit the K-Means clustering model and assign cluster labels to the data.

4. **Visualization**

   * Optionally reduce data dimensions to 2 using PCA.
   * Plot the clusters with different colors for each cluster.

5. **Evaluation**

   * Compute the Silhouette Score to evaluate the clustering quality.

---

## Output

* **Elbow Curve Plot:** Visualizes the inertias for different numbers of clusters.
* **Cluster Visualization:** A 2D scatter plot (after PCA reduction) showing the clusters in different colors.
* **Silhouette Score:** Printed on the console to indicate the quality of clustering.
