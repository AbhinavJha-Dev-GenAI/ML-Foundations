# Bayes' Theorem

The core of probabilistic reasoning.

## 🎯 Key Topics

### 1. The Formula
$$P(A|B) = \frac{P(B|A) P(A)}{P(B)}$$
- **$P(A|B)$ (Posterior)**: Probability of hypothesis $A$ given data $B$.
- **$P(B|A)$ (Likelihood)**: Probability of data $B$ given hypothesis $A$.
- **$P(A)$ (Prior)**: Our belief before seeing data.
- **$P(B)$ (Evidence)**: Probability of the data under all possible hypotheses.

### 2. Bayesian Inference
Unlike frequentist statistics (which looks at fixed parameters), Bayesian inference treats parameters as random variables and updates their distribution as new data arrives.

### 3. Naive Bayes Classifier
A simple but powerful classifier that assumes all features are independent (the "Naive" part). It calculates the posterior probability for each class and chooses the one with the highest value.

## 📚 Why it Matters
Bayes' Theorem allows models to "learn" and "update" their understanding as more data becomes available. It is the foundation of spam filters, medical diagnosis systems, and advanced uncertainty estimation in Deep Learning.
