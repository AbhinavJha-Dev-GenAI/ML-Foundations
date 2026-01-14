# Data Quality

Techniques for ensuring that the data used for modeling is accurate and consistent.

## 🎯 Key Topics

### 1. Data Profiling
The process of examining the data available and collecting statistics and information about that data.
- **Checklist**: Mean, Median, Min, Max, Null-count, Unique-count for every column.

### 2. Consistency Checks
Ensuring that data follows logical rules.
- **Example**: Age cannot be negative. Date of birth cannot be in the future.

### 3. Duplicate Removal
Redundant data can lead to over-representing certain patterns and causing overfitting in the training set.

### 4. Handling Imbalanced Data
If $99\%$ of your data is "not fraud" and $1\%$ is "fraud", the model will learn to just predict "not fraud" every time.
- **SMOTE**: Synthetically creating more samples for the minority class.
- **Undersampling**: Reducing the size of the majority class.

## 📚 Why it Matters
High-quality models require high-quality data. Identifying "silent" data bugs (like incorrect units or leakage) early in the pipeline saves weeks of debugging later.
