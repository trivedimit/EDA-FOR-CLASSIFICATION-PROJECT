# 🧠 EDA for Classification Project  
## Dataset: Customer Churn

This project focused on performing a comprehensive **Exploratory Data Analysis (EDA)** on a customer churn dataset, with the goal of identifying patterns and significant features that influence customer churn behavior.

---

## ✅ Summary of Steps

### 1. 🚀 Initial Setup & Data Overview
- Imported essential libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`
- Loaded the **Customer Churn dataset**
- Explored basic structure using `.info()`, `.describe()`, and `.head()`
- Checked column types and understood variable categories (categorical vs numerical)
- Reviewed the target variable `Exited` for class balance
  
### 2. 📊 Univariate Analysis
- Explored individual distributions of key features  
- Assessed value counts, skewness, and class balance
  
### 3. 🔗 Bivariate Statistical Testing
- Applied **Chi-Square Test** (categorical vs `Exited`)  
- Applied **ANOVA Test** (numerical vs `Exited`)  
- ✅ Selected only statistically significant features for further analysis
  
### 4. 📈 Visual Analytics (Seaborn)
- Clean and modern charts using `sns.set_theme()`  
- Grouped bar plots for categorical features vs `Exited`  
- Boxplots and histograms for numerical feature variation by `Exited`
  
### 5. 🚨 Missing Value Handling & Outlier Detection
- Checked for missing values  
- ✅ No missing values found — skipped imputation
- Used **Local Outlier Factor (LOF)** on numerical features  
- Identified and removed rows with extreme behavior  
- Resulted in a more stable, high-quality dataset



---

## 📌 Key Insights

- ✅ **Gender**, **Geography**, and **IsActiveMember** were **statistically significant** categorical predictors of churn  
- 📉 Customers with **higher Age** and **lower Balance** showed higher churn risk  
- 🧠 Visual analysis aligned well with statistical test outcomes, increasing trust in the selected features

---

## 🏁 Final Notes

This EDA phase provides a **robust foundation for predictive modeling**.  
The cleaned and statistically validated dataset is now ready for training classification models such as:

- Logistic Regression  
- Random Forest  
- XGBoost  
- Gradient Boosting

> ✅ A well-executed EDA ensures data is **relevant, interpretable, and ready for machine learning**.

---
