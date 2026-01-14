# Distributions

Recognizing patterns in data.

## 🎯 Key Topics

### 1. Normal (Gaussian) Distribution
The most important distribution in ML. Defined by mean ($\mu$) and variance ($\sigma^2$).
- **Central Limit Theorem**: The sum of many independent random variables tends toward a normal distribution, regardless of the original distribution.
- **Standard Normal**: $\mu=0, \sigma=1$.

### 2. Discrete Distributions
- **Bernoulli**: Single trial with two outcomes (Success/Failure).
- **Binomial**: Number of successes in $n$ independent Bernoulli trials.
- **Poisson**: Number of events occurring in a fixed interval of time or space.

### 3. Continuous Distributions
- **Exponential**: Time between events in a Poisson process.
- **Uniform**: All outcomes in a range are equally likely.
- **Long-tail (Power Law)**: A few events are very common, but most events are rare (e.g., word frequencies in NLP).

## 📚 Why it Matters
ML models often make assumptions about the distribution of data. For example, Linear Regression assumes errors are normally distributed. Recognizing the distribution of your data helps in choosing the right model and feature scaling techniques.
