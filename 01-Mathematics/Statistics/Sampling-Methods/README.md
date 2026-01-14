# Sampling Methods

Techniques for selecting a subset of data from a population.

## 🎯 Key Topics

### 1. Simple Random Sampling
Every member of the population has an equal chance of being selected.
- **Pros**: Easy to implement.
- **Cons**: Might miss small but important sub-groups.

### 2. Stratified Sampling
The population is divided into groups (strata), and samples are taken from each group proportionally.
- **ML Use Case**: Ensuring that training/test splits have the same class distribution as the original data.

### 3. Systematic Sampling
Every $k$-th member is selected (e.g., every 10th customer).

### 4. Cluster Sampling
The population is divided into clusters, and entire clusters are randomly selected.

## 📚 Why it Matters
We rarely have access to the entire "population" of data. Good sampling ensures that our data is **Representative**, meaning the conclusions we draw from our dataset will actually apply to the real world.
