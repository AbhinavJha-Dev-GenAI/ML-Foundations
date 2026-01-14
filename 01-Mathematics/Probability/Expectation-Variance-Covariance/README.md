# Expectation, Variance & Covariance

Describing the central tendency and spread of data.

## 🎯 Key Topics

### 1. Expectation (Mean)
The average value we expect to see if we repeat an experiment many times.
$$E[X] = \sum x P(x)$$

### 2. Variance
Measures how much the values of a random variable vary from the mean.
$$\text{Var}(X) = E[(X - E[X])^2]$$
- **Standard Deviation**: $\sqrt{\text{Var}(X)}$.

### 3. Covariance
Measures how two random variables change together.
- **Positive**: They grow together.
- **Negative**: One grows, the other shrinks.
- **Zero**: They have no linear relationship.

### 4. Correlation
A normalized version of covariance that ranges from -1 to 1. Unlike covariance, it is scale-independent.

## 📚 Why it Matters
In ML, the **Covariance Matrix** of a dataset is central to techniques like PCA. Understanding variance is key to the Bias-Variance tradeoff, which determines how well a model generalizes.
