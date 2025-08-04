# Titanic Dataset - Task 1: Data Cleaning & Preprocessing

This repository contains **Task 1** of my internship project: **Data Cleaning & Preprocessing** on the Titanic Dataset using Python and Pandas.

---

## 📌 **Task Objectives**

The main goals of Task 1 are to:
1. **Import and explore the dataset**
   - Load the dataset using `pandas.read_csv()`
   - Check the first few rows using `.head()`
   - Inspect data types and null values with `.info()` and `.isnull().sum()`

2. **Handle missing values**
   - Fill missing `Age` values with the median.
   - Fill missing `Embarked` values with the mode.
   - Drop or transform the `Cabin` column by creating a `Has_Cabin` flag.

3. **Encode categorical features**
   - Convert `Sex` to numeric (`male` → 0, `female` → 1).
   - Encode `Embarked` using one-hot encoding.
   - Extract passenger titles from `Name` and encode them (optional).

4. **Normalize/standardize numerical features**
   - Standardize `Age`, `Fare`, `SibSp`, and `Parch` using `StandardScaler` from `sklearn`.

5. **Visualize and remove outliers**
   - Visualize numerical features using boxplots (`seaborn`).
   - Detect and remove outliers using the IQR method.

---

## ✅ **Libraries Used**

- `pandas` for data manipulation
- `numpy` for numerical operations
- `seaborn` and `matplotlib` for data visualization
- `scikit-learn` for standardization
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
