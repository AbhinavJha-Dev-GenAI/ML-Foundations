# Cosine Similarity

Measuring orientation and similarity between vectors in high-dimensional space.

## 🎯 Key Topics

### 1. Formula
The cosine of the angle $\theta$ between vectors $A$ and $B$:
$$\text{similarity} = \cos(\theta) = \frac{A \cdot B}{\|A\| \|B\|}$$
- **Value $= 1$**: Identical direction (very similar).
- **Value $= 0$**: Orthogonal (not similar).
- **Value $= -1$**: Opposite directions.

### 2. Why Cosine?
Unlike Euclidean distance, cosine similarity measures the **angle**, not the magnitude. In NLP, two documents might have the same content but different lengths; cosine similarity will recognize them as similar regardless of length.

### 3. Applications
- **Word Embeddings**: Finding synonyms (e.g., "King" and "Queen").
- **Search Engines**: Ranking document relevance to a query.

## 📚 Why it Matters
In high-dimensional spaces (common in ML), distances become weird. Cosine similarity is a robust metric that captures semantic similarity even when the "scale" of data varies.
