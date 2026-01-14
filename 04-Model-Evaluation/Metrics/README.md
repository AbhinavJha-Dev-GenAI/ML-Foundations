# Metrics

Quantitative benchmarks used to assess the quality of an ML model.

## 🎯 Key Metrics

### 1. Classification Metrics
- **Accuracy**: (Correct / Total). Can be misleading in imbalanced datasets.
- **Precision**: (True Positive / Total Predicted Positive). "Of all the dogs we predicted, how many were actually dogs?" (Focus on quality).
- **Recall**: (True Positive / Total Actual Positive). "Of all the actual dogs, how many did we find?" (Focus on quantity).
- **F1-Score**: Harmonic mean of Precision and Recall. Best for imbalanced classes.
- **ROC-AUC**: Measures the model's ability to distinguish between classes at various thresholds.

### 2. Regression Metrics
- **MAE (Mean Absolute Error)**: Average absolute difference. Easy to interpret.
- **MSE (Mean Squared Error)**: Punishes larger errors more heavily.
- **RMSE**: Square root of MSE. Brings units back to the original scale.
- **R-Squared**: Measures the $ \%$ of variance in the target explained by the features.

### 3. Clustering Metrics
- **Silhouette Score**: Measures how similar a point is to its own cluster compared to others.

## 📚 Why it Matters
Choosing the wrong metric is a common mistake. If you optimize for Accuracy on a fraud detection task ($1\%$ fraud), a model that predicts "No Fraud" every time will have $99\%$ accuracy but will be completely useless.
