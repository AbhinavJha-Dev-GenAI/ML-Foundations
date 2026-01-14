# Learning Rate Schedules

Techniques for adjusting the learning rate during training to improve convergence.

## 🎯 Key Topics

### 1. The Problem
- **High Learning Rate**: Training may oscillate or overshoot the minimum.
- **Low Learning Rate**: Training is too slow or gets stuck in sub-optimal local minima.

### 2. Common Schedules
- **Step Decay**: Reduce the learning rate by a factor (e.g., 0.1) every $N$ epochs.
- **Exponential Decay**: $\eta_t = \eta_0 e^{-kt}$.
- **Cosine Annealing**: Decays the rate following a cosine curve, often combined with "restarts" (Warm Restarts).

### 3. Learning Rate Warm-up
Starting with a very small learning rate for the first few thousand steps to "stabilize" the weights before increasing it to the main rate. This is critical for training large models like Transformers.

## 📚 Why it Matters
A well-chosen schedule can be the difference between a model that converges to state-of-the-art accuracy and one that fails to learn altogether. It is one of the most important hyperparameters to tune.
