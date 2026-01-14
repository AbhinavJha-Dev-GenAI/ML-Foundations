# 03. Feature Engineering 🛠️🎨

Feature Engineering is the process of transforming raw data into meaningful inputs that improve the performance of machine learning models. As the saying goes: *"Better features beat a better algorithm."*

## 1. Handling Missing Values & Outliers 🧹

Models cannot process `NaN` values.
*   **Imputation**: Filling missing values with Mean, Median, Mode, or a constant.
*   **Outlier Detection**: Using Z-score or IQR (Interquartile Range) to identify and remove/clip extreme data points that might skew the model.

---

## 2. Encoding Categorical Data 🏷️

Turning "Text" categories into numbers.
*   **One-Hot Encoding**: Creates a binary column for each category. (Best for Nominal data like Color: Red, Blue).
*   **Label Encoding**: Assigns an integer (0, 1, 2) to each category. (Best for Ordinal data like Size: Small, Medium, Large).
*   **Target Encoding**: Replaces the category with the average target value for that category.

---

## 3. Scaling & Transformation 📊

Ensures that features with large ranges (e.g., Salary) don't dominate features with small ranges (e.g., Age).
*   **Standardization (Z-score)**: Scales data to have Mean=0 and StdDev=1.
*   **Normalization (Min-Max)**: Scales data to a range between 0 and 1.
*   **Log Transform**: Used for skewed data to make it closer to a normal distribution.

---

## 4. Dimensionality Reduction 📉

Reducing the number of features to improve speed and reduce overfitting.
*   **PCA (Principal Component Analysis)**: Linear reduction that preserves maximum variance.
*   **t-SNE / UMAP**: Non-linear reduction used for **Visualization** of high-dimensional data.

---

## 🛠️ Essential Snippet (Scaling with Scikit-Learn)

```python
from sklearn.preprocessing import StandardScaler

# 1. Initialize
scaler = StandardScaler()

# 2. Fit and Transform
# Note: Always fit only on training data, then transform both train and test!
X_train_scaled = scaler.fit_transform(X_train)
X_test_scaled = scaler.transform(X_test)
```

---

## 🚨 Summary
Feature Engineering is where the "Art" of data science lives. It requires domain knowledge and experimentation to find the specific representation of data that makes the problem easy for the model to solve.
