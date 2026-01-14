# KL-Divergence

Measuring the difference between two probability distributions.

## 🎯 Key Topics

### 1. Definition
Kullback-Leibler (KL) Divergence (also called Relative Entropy) measures how much information is lost when we use distribution $Q$ to approximate distribution $P$.
$$D_{KL}(P \| Q) = \sum P(x) \log \frac{P(x)}{Q(x)}$$

### 2. Properties
- **Non-Negative**: $D_{KL}(P \| Q) \geq 0$.
- **Non-Symmetric**: $D_{KL}(P \| Q) \neq D_{KL}(Q \| P)$. This is why it is called a "divergence" and not a "distance".

### 3. Applications
- **Variational Autoencoders (VAEs)**: Used to force the latent space distribution to match a standard normal distribution.
- **GANs**: Used to measure the difference between real and generated data distributions.

## 📚 Why it Matters
KL-Divergence is the standard way to compare distributions. It allows us to "shape" the internal representations of deep learning models to fit specific mathematical properties.
