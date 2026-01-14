# Bias-Variance Tradeoff

The fundamental tension between model simplicity and flexibility.

## 🎯 Key Topics

### 1. Bias (Underfitting)
Error from erroneous assumptions in the learning algorithm.
- **High Bias**: The model is too simple (e.g., using Linear Regression on non-linear data). It misses the complexity of the data.

### 2. Variance (Overfitting)
Error from sensitivity to small fluctuations in the training set.
- **High Variance**: The model is too complex (e.g., a very deep tree). it "memorizes" the noise in the training data and fails on new data.

### 3. The Tradeoff
As we increase model complexity, Bias decreases but Variance increases. The goal is to find the "Sweet Spot" that minimizes the **Total Error**.

### 4. Solutions
- **To fix High Bias**: Use more complex models, add features, reduce regularization.
- **To fix High Variance**: Use more data, use simpler models, add **Regularization** (L1/L2), use Ensemble methods.

## 📚 Why it Matters
The Bias-Variance tradeoff is the most important concept in model tuning. It explains why "bigger" isn't always "better" and guides every decision a data scientist makes during training.
