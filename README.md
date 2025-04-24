# Task-1-Elevate-Labs
# Titanic Dataset - Data Cleaning & Preprocessing

This project is part of my internship task at Elevate Labs, focused on preparing raw data for machine learning by cleaning and preprocessing the Titanic dataset.

## Objective

To clean, transform, and prepare the Titanic dataset using Python libraries for further machine learning tasks.

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for scaling)

## Steps Performed

### 1. Data Loading & Exploration
- Loaded the Titanic dataset into a Pandas DataFrame.
- Displayed basic information such as data types, null values, and basic stats.

### 2. Handling Missing Values
- Filled missing `Age` values using the **median**.
- Replaced missing values in `Embarked` with the **most frequent (mode)**.
- Dropped the `Cabin` column due to a high number of nulls.

### 3. Encoding Categorical Variables
- Converted categorical columns like `Sex` and `Embarked` into numerical using **one-hot encoding** (`pd.get_dummies`).

### 4. Feature Scaling
- Normalized numerical columns `Age` and `Fare` using **StandardScaler** from `sklearn`.

### 5. Outlier Detection & Removal
- Visualized outliers using **boxplots**.
- Removed outliers in `Age` and `Fare` using the **IQR (Interquartile Range)** method.

---

## Final Output
- A clean, numerical, and normalized dataset.
- Ready for machine learning model training.

---

## 📁 Files Included
- `Elevate labs internship task 1` – Jupyter notebook with all code
- `Titanic-Dataset` - Dataset 
- `README.md` – This file

