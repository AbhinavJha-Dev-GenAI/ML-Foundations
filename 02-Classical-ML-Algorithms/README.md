# 02. Classical ML Algorithms 🏛️⚙️

Before diving into Deep Learning, an engineer must master the classical algorithms. They are often faster, cheaper, and more interpretable than neural networks.

## 1. Supervised Learning: Regression 📉

Predicting a continuous number (e.g., Price, Temperature).
*   **Linear Regression**: Drawing the best-fit line.
*   **Polynomial Regression**: For non-linear data.
*   **Regulation (L1/L2)**: Ridge and Lasso to prevent overfitting.

---

## 2. Supervised Learning: Classification 🏷️

Predicting a category (e.g., Spam vs. Not Spam).
*   **Logistic Regression**: Predicts the probability of a class (using the Sigmoid function).
*   **Support Vector Machines (SVM)**: Finding the hyperplane that maximizes the "margin" between classes.
*   **K-Nearest Neighbors (KNN)**: Classifying based on the "votes" of the closest neighbors.
*   **Naive Bayes**: Fast, probability-based classifier (Great for text).

---

## 3. Tree-Based Models (The Production Standards) 🌲

*   **Decision Trees**: A flow-chart-like structure of "If-Else" rules.
*   **Random Forest**: An ensemble of trees that "vote" to reduce variance.
*   **XGBoost / LightGBM**: "Gradient Boosting" where each new tree tries to fix the errors of the previous ones. **Standard for tabular data.**

---

## 4. Unsupervised Learning 🧩

Finding hidden patterns in unlabeled data.
*   **K-Means Clustering**: Grouping data into $k$ clusters based on distance.
*   **Hierarchical Clustering**: Building a "tree" of clusters.
*   **DBSCAN**: Density-based clustering (Excellent for finding clusters of arbitrary shapes).

---

## 🛠️ Essential Snippet (XGBoost Classifier)

```python
import xgboost as xgb
from sklearn.model_selection import train_test_split

# 1. Load Data
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)

# 2. Define Model
model = xgb.XGBClassifier(
    n_estimators=100, 
    learning_rate=0.1, 
    max_depth=5
)

# 3. Fit
model.fit(X_train, y_train)

# 4. Predict
predictions = model.predict(X_test)
```

---

## 🚨 Summary
Classical ML is the bread and butter of industry. If you can solve a problem with **Logistic Regression** or **Random Forest**, don't use a Neural Network. Simplicity is a feature, not a bug.
