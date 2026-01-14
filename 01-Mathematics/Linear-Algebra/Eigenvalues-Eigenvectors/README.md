# Eigenvalues & Eigenvectors

Understanding linear transformations and their characteristic directions.

## 🎯 Key Topics

### 1. Core Definition
For a square matrix $A$, an **eigenvector** $v$ and its corresponding **eigenvalue** $\lambda$ satisfy:
$$Av = \lambda v$$
This means that when the transformation $A$ is applied to $v$, its direction stays the same; it only scales by $\lambda$.

### 2. Characteristic Equation
Found by solving $\det(A - \lambda I) = 0$.

### 3. Principal Component Analysis (PCA)
PCA uses the eigenvectors of the data's covariance matrix to identify the directions of maximum variance. These directions are the "principal components" that allow us to reduce dimensions while keeping the most important information.

## 📚 Why it Matters
Eigen-decomposition is the "MRI" of a matrix. It reveals the internal structure, which is used in Google's PageRank, recommendation engines, and high-dimensional data visualization.
