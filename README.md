# Palmer Penguins Species Clustering

## Objective
To apply unsupervised learning techniques to cluster penguins based on physical characteristics and evaluate how closely clusters align with biological species.

## Techniques Used
- Data Cleaning & Imputation
- Feature Engineering (bill_ratio)
- Standardization
- K-Means Clustering
- Silhouette Score
- Elbow Method
- PCA for Visualization

## Feature Engineering
A new feature `bill_ratio` was created to represent beak shape. Silhouette Score improved after inclusion, indicating improved cluster separability.

## Model Selection
Although k=2 yielded the highest silhouette score, k=3 was selected to align with known biological species, ensuring interpretability and domain consistency.

## Validation
- Silhouette Score
- Cluster vs Species Crosstab
- PCA Visualization
