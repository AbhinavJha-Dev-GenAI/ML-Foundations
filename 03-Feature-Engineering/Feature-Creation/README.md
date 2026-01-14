# Feature Creation

Methods for generating new informative variables from raw input data.

## 🎯 Key Topics

### 1. Polynomial Features
Creating interaction terms and power terms (e.g., $x_1, x_2, x_1^2, x_2^2, x_1 x_2$) to allow linear models to capture non-linear relationships.

### 2. Interaction Features
Combining two or more features to capture dependencies (e.g., combining "Width" and "Height" into "Area").

### 3. Binning and Discretization
Converting continuous features into categories.
- **Example**: Converting "Age" into "Child", "Teen", "Adult", "Senior". This helps capture non-linear effects within age groups.

### 4. Mathematical Transformations
- **Log Transform**: Used to reduce the skewness of a distribution (e.g., for income or population data).
- **Box-Cox**: A generalized power transformation to make data more "normal-like".

## 📚 Why it Matters
Feature creation is where domain expertise meets data science. A single well-crafted feature (like "Distance from City Center" for house prices) can often be more valuable than tuning model hyperparameters.
