# Feature Extraction (PCA)
Transforming the high-dimensional data into a lower-dimensional space.

* Principal Component Analysis (PCA): A deterministic linear transformation that rotates the data into a new coordinate system.
    * Goal: To find new axes (Principal Components) that maximize the spread (variance) of the data.
    * Mechanism: It performs Eigen-decomposition on the Covariance Matrix.
    * PC1: The direction of maximum variance.
    * PC2: Orthogonal to PC1, capturing the remaining variance.
