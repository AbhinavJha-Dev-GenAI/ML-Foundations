# Error Analysis

The process of manually examining samples that the model misclassified to identify systematic failures.

## 🎯 Key Topics

### 1. The Confusion Matrix
A table layout that allows visualization of the performance of an algorithm.
- **TP (True Positive)** / **TN (True Negative)**: Correct predictions.
- **FP (False Positive)**: Type I Error (False Alarm).
- **FN (False Negative)**: Type II Error (Missed detection).

### 2. Residual Analysis
For regression, plotting the difference between predicted and actual values.
- **Ideal**: Residuals are randomly scattered around zero.
- **Patterned Residuals**: If you see a curve, your model is missing a non-linear relationship.

### 3. Learning Curves
Plotting Training Error and Validation Error against the number of training samples.
- **High Gap**: Indicates high variance (Overfitting).
- **Low Accuracy for both**: Indicates high bias (Underfitting).

## 📚 Why it Matters
Numbers like "90% Accuracy" don't tell the whole story. Error analysis tells you *where* and *why* the model is failing (e.g., "The model always misclassifies cats as dogs if the background is green"). This directed feedback is how you improve models.
