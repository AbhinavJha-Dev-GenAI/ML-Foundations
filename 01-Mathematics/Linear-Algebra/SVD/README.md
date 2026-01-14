# Singular Value Decomposition (SVD)

A powerful matrix factorization technique used in compression and recommendation systems.

## 🎯 Key Topics

### 1. The Decomposition
SVD decomposes any $m \times n$ matrix $A$ into:
$$A = U \Sigma V^T$$
- **$U$**: Left singular vectors (Orthogonal).
- **$\Sigma$**: Diagonal matrix of singular values (Importance of each component).
- **$V$**: Right singular vectors (Orthogonal).

### 2. Low-rank Approximation
By keeping only the top $k$ singular values in $\Sigma$, we can approximate $A$ with a much smaller matrix. This is the basis for image compression and noise reduction.

### 3. Applications
- **Recommendation Systems**: Latent Factor models (e.g., Netflix Prize).
- **NLP**: Latent Semantic Analysis (LSA) to find relationships between documents.

## 📚 Why it Matters
Unlike Eigen-decomposition, SVD works on *any* matrix (not just square ones). It is the mathematical engine behind massive-scale data compression and information retrieval.
