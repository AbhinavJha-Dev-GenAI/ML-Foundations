# Data Processing

The initial steps to clean and transform raw data into a usable format.

## 🎯 Key Topics

### 1. Handling Missing Values
Data often has gaps. Strategies include:
- **Deletion**: Removing rows/columns with missing values (only if small % or data is huge).
- **Imputation**: Filling gaps with Mean, Median, Mode, or using models like KNN to predict the missing value.

### 2. Outlier Detection and Treatment
Outliers can skew results. Techniques include:
- **Z-Score**: Identify points $> 3$ standard deviations from the mean.
- **IQR (Interquartile Range)**: Points outside $[Q1 - 1.5 \cdot IQR, Q3 + 1.5 \cdot IQR]$.

### 3. Feature Scaling
Most algorithms (like SVM, KNN, or Neural Nets) are sensitive to the scale of features.
- **Normalization (Min-Max)**: Squishing values between 0 and 1.
- **Standardization (Z-score)**: Centering data around 0 with a standard deviation of 1.

### 4. Encoding Categorical Variables
Machines only understand numbers.
- **One-Hot Encoding**: Creating binary columns for each category (e.g., Red $\rightarrow [1, 0, 0]$).
- **Label Encoding**: Assigning a number to each category ($0, 1, 2$).

## 📚 Why it Matters
"Garbage In, Garbage Out". Data processing is often 80% of a data scientist's job. Without clean, scaled, and correctly encoded data, even the most advanced model will fail to produce useful results.
