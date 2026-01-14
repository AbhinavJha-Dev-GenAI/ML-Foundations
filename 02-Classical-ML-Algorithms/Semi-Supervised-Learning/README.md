# Semi-Supervised Learning

A hybrid approach that uses a small amount of labeled data alongside a large amount of unlabeled data.

## 🎯 Key Topics

### 1. The Core Idea
In many real-world cases, labeling data is expensive (requires humans), but raw data is abundant. Semi-supervised learning uses the small labeled set to "guide" the learning from the large unlabeled set.

### 2. Common Techniques
- **Self-Training**: The model makes predictions on unlabeled data, and its most confident predictions are added to the training set as "pseudo-labels".
- **Graph-based Methods**: Representing data as a graph where nodes are data points and edges represent similarity. Labels are then propagated through the graph.

### 3. Assumptions
- **Continuity Assumption**: Points that are close to each other are likely to have the same label.
- **Cluster Assumption**: Data tends to form clusters, and points in the same cluster share a label.

## 📚 Why it Matters
This is how modern AI systems handle massive datasets (like the whole internet). It is particularly powerful in NLP and Computer Vision, where labeling every image or sentence is impossible.
