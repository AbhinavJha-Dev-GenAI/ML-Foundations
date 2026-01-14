# Convex vs Non-Convex Optimization

Distinguishing between easy and hard optimization problems.

## 🎯 Key Topics

### 1. Convex Functions
A function is convex if a line segment between any two points on the graph lies above the graph.
- **Property**: Any local minimum is also the **Global Minimum**.
- **ML Models**: Linear Regression, Logistic Regression, and SVMs (with certain kernels) are convex problems.

### 2. Non-Convex Functions
Functions with multiple local minima, plateaus, and hills.
- **The Challenge**: An optimizer might get stuck in a "shallow" local minimum and never find the global best.
- **Deep Learning**: Neural Networks are inherently non-convex.

### 3. Local vs Global Optima
In deep learning, we rarely find the "Global" optimum. However, research suggests that for large enough networks, most local optima are "good enough" for practical use.

## 📚 Why it Matters
Knowing if your problem is convex tells you if you can guarantee an optimal solution. For non-convex problems (like Deep Learning), the focus shifts from "finding the best" to "finding a good enough" solution efficiently.
