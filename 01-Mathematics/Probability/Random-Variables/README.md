# Random Variables

Mathematical mapping of outcomes to real numbers.

## 🎯 Key Topics

### 1. What is a Random Variable (RV)?
It is not a "variable" in the traditional coding sense, but rather a **function** that assigns a real number to each outcome in a probability space.
- **Example**: If you flip two coins, the number of "Heads" is a random variable $X$ that can take values $\{0, 1, 2\}$.

### 2. Discrete vs Continuous RVs
- **Discrete**: Can take a countable number of values. Described by a **Probability Mass Function (PMF)**.
- **Continuous**: Can take any value in a range (e.g., height, temperature). Described by a **Probability Density Function (PDF)**.

### 3. Cumulative Distribution Function (CDF)
The probability that the random variable $X$ will take a value less than or equal to $x$:
$$F_X(x) = P(X \leq x)$$
- **Discrete**: Sum of PMF values.
- **Continuous**: Integral of the PDF.

## 📚 Why it Matters
Random variables allow us to quantify outcomes and perform mathematical operations on them. Every data feature in ML is essentially a realization of a random variable.
