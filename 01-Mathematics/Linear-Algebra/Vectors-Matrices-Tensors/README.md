# Vectors, Matrices & Tensors

Fundamental units of data representation in Machine Learning.

## 🎯 Key Topics

### 1. Vectors
A vector is an ordered array of numbers. In ML, a vector often represents a single data point (e.g., a house's features like size and price).
- **Notation**: Usually denoted as $\mathbf{v} \in \mathbb{R}^n$.
- **Geometric View**: A direction and magnitude in $n$-dimensional space.

### 2. Matrices
A matrix is a 2D array of numbers. It represents a collection of vectors or a linear transformation.
- **Data Representation**: Rows often represent samples, and columns represent features.
- **Rank**: The number of linearly independent rows or columns in a matrix.

### 3. Tensors
A tensor is a generalization of scalars (0D), vectors (1D), and matrices (2D) to higher dimensions.
- **Deep Learning**: Images are often represented as 3D tensors (Height x Width x Channels), and video can be 4D.

## 📚 Why it Matters
All data in ML must be converted into these numerical structures before a model can "learn" from it. Vectorization allows us to use highly optimized hardware (GPUs) to perform operations in parallel.
