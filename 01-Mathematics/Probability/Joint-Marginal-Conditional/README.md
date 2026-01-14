# Joint, Marginal & Conditional Probability

Relationships between multiple random variables.

## 🎯 Key Topics

### 1. Conditional Probability
The probability of $A$ occurring given that $B$ has already occurred:
$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

### 2. Joint Probability
The probability of both $A$ and $B$ occurring simultaneously: $P(A, B)$.
- **Product Rule**: $P(A, B) = P(A|B) P(B)$.

### 3. Marginal Probability
The probability of a single variable $A$ regardless of other variables.
- **Sum Rule**: $P(A) = \sum_B P(A, B)$ (for discrete).
- **Integral Rule**: $P(A) = \int P(A, B) dB$ (for continuous).

### 4. Independence
Two variables are independent if knowing the outcome of one tells you nothing about the other:
$$P(A, B) = P(A) P(B)$$

## 📚 Why it Matters
These rules are the "arithmetic" of probability. They allow us to break down complex systems into simpler conditional relationships, which is how Probabilistic Graphical Models and most ML frameworks operate.
