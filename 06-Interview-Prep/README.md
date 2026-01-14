# 06. ML-Foundations Interview Preparation 🧠🧱

Foundational questions for any Machine Learning or Data Science role.

## 1. Probability & Statistics 📖

*   **Q: What is the Central Limit Theorem (CLT) and why is it important?**
    - *A:* CLT states that the distribution of many independent random variables tends toward a normal distribution, regardless of their original distribution. This allows us to use normal-distribution based tests (like Z-tests) on almost any large dataset.
*   **Q: Explain the difference between "Correlation" and "Causation."**
    - *A:* Correlation means two things happen at the same time. Causation means one thing *makes* the other happen. (e.g., Ice cream sales and drowning are correlated, but heat causes both).
*   **Q: What is a $p$-value?**
    - *A:* The probability that you would see results as extreme as yours if the "Null Hypothesis" (no effect) were true. A small $p$-value ($<0.05$) suggests the effect is likely real.

---

## 2. Algorithms & Evaluation 🏗️

*   **Q: How does a Random Forest reduce variance?**
    - *A:* It uses **Bagging** (Bootstrap Aggregating). It trains many trees on different subsets of the data and averages their results, which cancels out the individual noise/overfitting of any single tree.
*   **Q: Precision vs Recall: When to prioritize which?**
    - *A:* Prioritize **Precision** when a False Positive is expensive (e.g., Jail time, High-value spam). Prioritize **Recall** when a False Negative is dangerous (e.g., Cancer detection, Failing engine part).
*   **Q: What is the Bias-Variance Tradeoff?**
    - *A:* High bias leads to underfitting (too simple). High variance leads to overfitting (too complex). The goal is to find the "Sweet Spot" in the middle.

---

## 3. Practical Data Scenarios 🧪

*   **Q: What do you do if your dataset is highly imbalanced?**
    - *A:* 1. Don't use Accuracy (use Precision/Recall/F1). 2. Resample (Oversample the minority class or Undersample the majority). 3. Use specialized algorithms like XGBoost that have "scale_pos_weight" parameters.
*   **Q: Why do we need to scale features before using SVM or KNN?**
    - *A:* These algorithms rely on **Euclidean Distance**. If one feature (Salary: 100k) has a much larger range than another (Age: 25), the distance calculation will be dominated by Salary, regardless of how important Age is.

---

## 🎯 ML Foundations Cheat Sheet
1. **Best for Tabular Data**: Gradient Boosting (XGBoost/LightGBM).
2. **Best for Text/Fast**: Naive Bayes.
3. **Best for Preprocessing**: Standardization (Mean=0, Std=1).
4. **Best for Validation**: 5-Fold Cross-Validation.
