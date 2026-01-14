# Orthogonality & Projections

Geometric interpretation of data fitting and optimization.

## 🎯 Key Topics

### 1. Orthogonality
Two vectors are orthogonal if their dot product is zero ($x \cdot y = 0$). Geometrically, they are perpendicular. An orthogonal matrix $Q$ has the property $Q^T Q = I$.

### 2. Orthogonal Projections
Projecting a point onto a line or plane is the closest point to that line/plane. In Linear Regression, the "Best Fit" line is found by projecting the target vector $y$ onto the column space of the feature matrix $X$.

### 3. Gram-Schmidt Process
A method to transform a set of linearly independent vectors into an orthonormal set (orthogonal and unit length).

## 📚 Why it Matters
Optimization often involves finding the "shortest distance" to a solution. Orthogonality simplifies these calculations significantly and is the geometric reason why Linear Regression works.
