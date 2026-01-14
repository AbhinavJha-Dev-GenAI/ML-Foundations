# Matrix Operations

Computational building blocks for ML models.

## 🎯 Key Topics

### 1. Matrix Multiplication (Dot Product)
This is the most frequent operation in ML. In a Neural Network, $y = \sigma(Wx + b)$, where $Wx$ is a matrix-vector product.
- **Rule**: To multiply $A (m \times n)$ and $B (n \times p)$, the number of columns in $A$ must equal the number of rows in $B$.
- **Geometric View**: A transformation of space.

### 2. Transpose and Inverse
- **Transpose ($A^T$)**: Flipping a matrix over its diagonal. Used in the Normal Equation for Linear Regression.
- **Inverse ($A^{-1}$)**: A matrix $A^{-1}$ such that $A A^{-1} = I$. Only exists for non-singular (square and full-rank) matrices.

### 3. Determinants and Trace
- **Determinant**: A value that describes the "scaling factor" of a transformation. If $\det(A) = 0$, the matrix is singular and cannot be inverted.
- **Trace**: The sum of diagonal elements.

## 📚 Why it Matters
Understanding these operations is crucial for optimizing models. For example, knowing that $(AB)^T = B^T A^T$ helps in deriving gradients for backpropagation.
