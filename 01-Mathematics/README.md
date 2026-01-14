# 01. Mathematics for Machine Learning 📐🧠

Mathematics is the language of machine learning. Understanding the underlying math allows you to debug models, optimize performance, and understand new research.

## 1. Linear Algebra 🧬

The foundation for handling large datasets and neural networks.
*   **Vectors & Matrices**: How we represent data points and layers.
*   **Dot Product**: The core operation in neural networks (projection and similarity).
*   **Matrix Multiplication**: Applying transformations at scale.
*   **Eigendecomposition & PCA**: Understanding the "principal axes" of your data to reduce noise.
*   **Singular Value Decomposition (SVD)**: Used in recommendation systems (Latent Factor models) and compression.

---

## 2. Calculus 📉

Calculus is how models "learn."
*   **Derivatives**: The "slope" or "rate of change."
*   **Partial Derivatives**: How much does one specific weight contribute to the total error?
*   **Chain Rule**: The engine behind **Backpropagation**.
*   **Gradient Descent**: Using the derivative to find the way "downhill" to minimum error.

---

## 3. Probability & Statistics 📊

How to handle uncertainty and make decisions from data.
*   **Distributions**: Normal (Gaussian), Binomial, and Poisson (The shapes of data).
*   **Bayes' Theorem**: Updating our belief about a model based on new evidence.
*   **Hypothesis Testing**: Is this model better by chance or is it a statistically significant improvement?
*   **P-values & Confidence Intervals**: Quantifying how sure we are about our results.

---

## 🛠️ Essential Concept: The Normal Distribution

Most ML algorithms (like Linear Regression) assume that the "noise" in your data follows a **Normal Distribution**.
- **Mean ($\mu$)**: The center of the data.
- **Variance ($\sigma^2$)**: How spread out the data is.
- **68-95-99.7 Rule**: In a normal distribution, 95% of your data falls within 2 standard deviations of the mean.

---

## 📊 Summary
Math isn't just theory; it's a tool. When your model isn't converging, or your accuracy is fluctuating, the answer is usually hidden in the **Calculus of the optimizer** or the **Statistics of the data**.
