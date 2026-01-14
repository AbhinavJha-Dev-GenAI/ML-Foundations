# Entropy & Cross-Entropy

Measuring information and loss in probabilistic models.

## 🎯 Key Topics

### 1. Shannon Entropy
Measures the average "surprise" or uncertainty in a distribution.
$$H(X) = - \sum p(x) \log p(x)$$
- **High Entropy**: High uncertainty (e.g., a fair coin).
- **Low Entropy**: High certainty (e.g., a biased coin).

### 2. Cross-Entropy
Measures how much one distribution $q$ differs from the "true" distribution $p$.
$$H(p, q) = - \sum p(x) \log q(x)$$

### 3. Use in Machine Learning
In classification, we use Cross-Entropy as a **Loss Function**. $p$ is the ground truth (one-hot label), and $q$ is the model's predicted probability. Minimizing cross-entropy is equivalent to making our predictions match the ground truth.

## 📚 Why it Matters
Entropy is the fundamental unit of information. Cross-entropy is the standard loss function for nearly all classification tasks in modern Neural Networks.
