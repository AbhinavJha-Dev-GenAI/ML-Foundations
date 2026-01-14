# Ensemble Methods

Techniques that combine multiple base models to create a stronger, more robust predictor.

## 🎯 Key Topics

### 1. Bagging (Bootstrap Aggregating)
Reducing variance by training multiple models on different subsets of the data and averaging their predictions.
- **Example**: **Random Forest** (An ensemble of many Decision Trees).

### 2. Boosting
Reducing bias by training models sequentially, where each new model tries to correct the errors made by previous ones.
- **Examples**: XGBoost, LightGBM, CatBoost. These are often the "winning" algorithms in Kaggle competitions.

### 3. Stacking
Training a "Meta-model" that learns how to best combine the predictions of several different base models (e.g., combining a Linear Regression and a KNN).

## 📚 Why it Matters
Ensemble methods follow the "Wisdom of the Crowd". A group of "weak" models can often outperform a single "strong" model. They are the industry standard for high-performance tabular data tasks.
