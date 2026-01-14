# 04. Model Evaluation & Validation 🎯📏

Evaluation is how we measure if our model actually works and how it will perform in the real world.

## 1. Validation Strategies 🛡️

*   **Train/Test Split**: Dividing your data into two sets.
*   **K-Fold Cross-Validation**: Dividing data into $k$ parts, training $k$ times, and averaging the results. This is the most reliable way to estimate performance on a small dataset.

---

## 2. Classification Metrics 🏷️

Don't just look at **Accuracy**, especially if your data is imbalanced (e.g., 99% non-fraud, 1% fraud)!

| Metric | Formula | Best For... |
| :--- | :--- | :--- |
| **Precision** | $TP / (TP + FP)$ | Minimizing False Positives (e.g., Spam filter). |
| **Recall** | $TP / (TP + FN)$ | Minimizing False Negatives (e.g., Cancer detection). |
| **F1-Score** | Harmonic mean of P & R | Balancing both Precision and Recall. |
| **ROC-AUC** | Area under the curve | Measuring the model's ability to distinguish between classes. |

---

## 3. Regression Metrics 📉

*   **MSE (Mean Squared Error)**: Penalizes large errors heavily.
*   **MAE (Mean Absolute Error)**: More robust to outliers.
*   **R-Squared ($R^2$)**: How much of the variance in the target is explained by the model?

---

## 4. The Bias-Variance Tradeoff ⚖️

*   **High Bias (Underfitting)**: Model is too simple. Solution: More features, complex model.
*   **High Variance (Overfitting)**: Model is too complex and learns noise. Solution: Regularization, more data, simpler model.

---

## 🛠️ Essential Snippet (Cross-Validation)

```python
from sklearn.model_selection import cross_val_score
from sklearn.ensemble import RandomForestClassifier

# 1. Define Model
clf = RandomForestClassifier()

# 2. Run 5-Fold Cross Validation
scores = cross_val_score(clf, X, y, cv=5)

print(f"Mean Accuracy: {scores.mean():.2f}")
print(f"Std Deviation: {scores.std():.2f}")
```

---

## 🌍 Summary
A model with 99% accuracy is often too good to be true. Always analyze the **Confusion Matrix** and use **Cross-Validation** to ensure your model hasn't just memorized the training set.
