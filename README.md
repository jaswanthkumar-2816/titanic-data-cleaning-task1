# Titanic Data Cleaning & Preprocessing

### 🎯 Task 1 – AI & ML Internship

This project involves cleaning and preprocessing the Titanic dataset to prepare it for machine learning models.

---

### ✅ Steps Completed:
- Loaded Titanic dataset
- Handled missing values (Age, Embarked)
- Dropped irrelevant column (Cabin)
- Encoded categorical features (Sex, Embarked)
- Standardized numerical columns (Age, Fare)
- Removed outliers in Fare using IQR
- Saved cleaned data

---

### 📁 Files:
- `task1_preprocessing.ipynb` – Notebook with all code
- `titanic_cleaned.csv` – Final cleaned dataset
- `README.md` – Task summary

---

### 👨‍💻 Tools Used:
Python, Pandas, NumPy, Seaborn, Scikit-learn

---

### 🔗 Dataset Source:
https://www.kaggle.com/datasets/yasserh/titanic-dataset
---

## ❓ Interview Questions & Answers

**1. What are the different types of missing data?**  
- MCAR (Missing Completely At Random)  
- MAR (Missing At Random)  
- MNAR (Missing Not At Random)

**2. How do you handle categorical variables?**  
- Use Label Encoding or One-Hot Encoding  
- One-Hot for non-ordinal categories (like City)  
- Label for ordinal categories (like Education level)

**3. What is the difference between normalization and standardization?**  
- Normalization scales data to [0,1]  
- Standardization transforms data to have mean=0 and std=1

**4. How do you detect outliers?**  
- Using boxplots, z-score, or IQR method

**5. Why is preprocessing important in ML?**  
- Ensures data is clean, consistent, and suitable for training models  
- Prevents bias or poor performance

**6. What is one-hot encoding vs label encoding?**  
- One-Hot: Converts category into binary columns  
- Label: Assigns a number to each category (e.g., Male=0, Female=1)

**7. How do you handle data imbalance?**  
- Oversampling minority class (SMOTE),  
- Undersampling majority class,  
- Using weighted models

**8. Can preprocessing affect model accuracy?**  
- Yes, good preprocessing can significantly improve model performance.

---
