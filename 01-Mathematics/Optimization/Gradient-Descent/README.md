# Gradient Descent

An iterative optimization algorithm for finding the minimum of a function.

## 🎯 Key Topics

### 1. The Core Idea
If you are standing on a foggy mountain and want to reach the bottom, you feel the slope of the ground and take a step in the direction of the steepest descent. In ML, the "mountain" is the Loss Function, and the "steps" update the model weights.
- **Update Rule**: $\theta = \theta - \eta \cdot \nabla J(\theta)$
- **$\eta$ (Learning Rate)**: The size of the step.

### 2. Variants
- **Batch Gradient Descent**: Uses the entire dataset to calculate the gradient. Slow but stable.
- **Stochastic Gradient Descent (SGD)**: Uses one sample at a time. Fast but noisy.
- **Mini-batch GD**: The industry standard. Uses a small batch (e.g., 32 or 64 samples) to strike a balance.

### 3. Advanced Optimizers
Pure GD often gets stuck or oscillates. Modern optimizers add "momentum" or "adaptive rates":
- **Momentum**: Accelerates GD in the relevant direction and dampens oscillations.
- **Adam (Adaptive Moment Estimation)**: Calculates adaptive learning rates for each parameter. It is the most popular optimizer today.

## 📚 Why it Matters
Gradient Descent is the "heartbeat" of modern Machine Learning. Without it, training deep neural networks with millions of parameters would be computationally impossible.
