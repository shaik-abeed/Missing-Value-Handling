# Missing Value Handling in Machine Learning

## Project Overview

Missing values are one of the most common problems in real-world datasets. This project demonstrates different techniques for identifying, analyzing, and handling missing values using Python and Scikit-learn.

---

## Objectives

- Detect missing values
- Calculate missing value percentage
- Remove missing values using row and column deletion
- Handle missing values using statistical imputation
- Compare different imputation techniques

---

## Dataset

A synthetic dataset was created to demonstrate missing value handling techniques. Missing values were intentionally introduced into multiple features to simulate real-world scenarios.

---

## Techniques Covered

### 1. Missing Value Detection

- isnull()
- sum()
- percentage of missing values

### 2. Removing Missing Values

- dropna()
- Drop Rows
- Drop Columns

### 3. Statistical Imputation

- Mean Imputation
- Median Imputation
- Mode Imputation

### 4. Advanced Imputation

- SimpleImputer
- IterativeImputer
- KNNImputer

---

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Visualizations

### Missing Value Heatmap

![Heatmap]<img width="552" height="518" alt="Missing_values_heatmap" src="https://github.com/user-attachments/assets/4f9cb5de-eb46-4f1e-89fe-808a495bf5e7" />


### Missing Values Count

![Count]<img width="552" height="502" alt="Missing_values_per_feature" src="https://github.com/user-attachments/assets/bbabc652-cc14-4f9f-8464-52125a8ea8fa" />


---

## Results

- Compared multiple missing value handling strategies.
- Learned advantages and disadvantages of each method.
- Understood when each imputation technique should be applied.

---

## Future Improvements

- Multiple Imputation (MICE)
- MissForest Imputation
- Deep Learning-based Imputation
- Comparison on real-world datasets

---

## Repository Structure

```
Missing-Value-Handling
│
├── handling_missing_values.ipynb
├── handling_missing_values.py
├── README.md
├── requirements.txt
└── images
```

---
