# 📦 Exploratory Data Analysis (EDA2) — Product-Based Case Study

This repository contains the complete code and visualizations from the second EDA case study, focused on customer purchase behavior for a private retail company. The dataset includes one month of purchase summaries for high-volume products.

---

## 📂 Datasets Used

- `train.csv`: Customer purchase records including product categories and purchase amounts
- `test.csv`: Similar structure, excluding the `Purchase` column

---

## 🎯 Problem Statement

A private retail company (XYZ) shared customer purchase data for selected high-volume products. The goal is to explore trends and patterns in customer behavior across demographics, product categories, and city segments.

---

## 🧠 Key Steps

1. **Data Loading & Inspection**
   - Imported training and testing datasets
   - Dropped `Purchase` column from training data for uniformity
   - Concatenated both datasets for unified analysis

2. **Data Cleaning**
   - Checked for duplicates and null values
   - Imputed missing values in `Product_Category_2` and `Product_Category_3` with a new category `21`
   - Converted relevant columns to categorical types

3. **Feature Engineering**
   - Mapped `Gender` to binary values (F → 0, M → 1)
   - Standardized `Stay_In_Current_City_Years` by replacing '4+' with 4

4. **Univariate & Bivariate Analysis**
   - Countplots for `Gender`, `Age`, `Occupation`, `City_Category`, `Marital_Status`
   - Pie charts for city and marital status distributions
   - Heatmap showing product affinity by age group
   - FacetGrid plots for multi-dimensional slicing (e.g., Age vs Gender vs City)

5. **Statistical Summary**
   - Descriptive statistics for numerical columns
   - Distribution analysis for categorical features

---

## 📊 Visualizations Included

- Countplots (Gender, Age, Occupation, Stay Duration)
- Pie charts (City Category, Marital Status)
- Heatmaps (Product Affinity by Age Group, Missing Values)
- FacetGrid plots (Age distribution across Gender and City)

---

## ⚠️ Challenges Faced

- **Missing values** in product categories — handled via imputation with category `21`
- **Encoding issues** — resolved during CSV import
- **Syntax errors** — corrected in plotting sections for clean execution

---

## 📎 Insights & Observations

- Majority of users are aged 26–35 and reside in City Category B
- Product affinity varies significantly across age groups
- Gender distribution is slightly skewed toward male users
- Occupation and marital status show distinct patterns by gender

---

## 👥 Collaborators

Special thanks to:
- **Pranav Jaipurkar**
- **Chirag Jhumkawala**
- **Sandhya Hinduja**

for their support and collaboration during the session.

---

## 🚀 Next Steps

- Extend analysis to predictive modeling (e.g., purchase prediction)
- Share findings via LinkedIn and invite feedback
- Explore clustering and segmentation for targeted marketing


