# Validation Strategies

Techniques for partitioning data to prevent overfitting and ensure robust performance.

## 🎯 Key Topics

### 1. Train-Test Split
Dividing the data into a training set and a hold-out test set (usually 80/20). The test set should *never* be used during training or hyperparameter tuning.

### 2. K-Fold Cross-Validation
1. Split the data into $K$ equal parts (folds).
2. Train on $K-1$ folds and test on the remaining fold.
3. Repeat $K$ times and average the results.
- **Pros**: Reduces the variance of the performance estimate.

### 3. Stratified K-Fold
Same as K-Fold, but ensures that each fold has the same percentage of samples of each target class as the complete set. Essential for imbalanced data.

### 4. Time-Series Split
For data where time matters (e.g., stock prices). We cannot use future data to predict the past, so the training set always comes before the test set chronologically.

## 📚 Why it Matters
A model that performs well on training data but poorly on a validation set is "Overfitting". Proper validation strategies allow us to simulate how the model will perform in the real world on data it has never seen before.
