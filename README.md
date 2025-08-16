# 🧪 Exploratory Data Analysis (EDA) — One-Day Session

This repository contains the complete code and insights from a one-day hands-on EDA session focused on two real-world case studies:

- **Case Study 1**: Food Delivery Service Dataset (Service-Based)
- **Case Study 2**: Product Dataset (Product-Based)

---

## 📂 Datasets Used

- `zomato.csv`: Restaurant-level data including ratings, delivery options, cuisine types, and geographic details.
- `Country-Code.xlsx`: Mapping of country codes to country names.

---

## 🔍 Objectives

- Perform structured EDA on both datasets
- Identify data quality issues, outliers, and missing values
- Visualize key patterns across cities, countries, ratings, and delivery options
- Derive actionable insights for business and product strategy

---

## 🧠 Key Steps

1. **Data Loading & Inspection**
   - Used `pandas`, `numpy`, `matplotlib`, and `seaborn`
   - Checked data types, null values, and duplicates

2. **Data Cleaning**
   - Removed rows with missing values in `Cuisines`
   - Merged country codes for clarity

3. **Univariate Analysis**
   - Pie charts for top countries and cities
   - Count plots for rating colors, delivery options, and city categories

4. **Bivariate Analysis**
   - Clustered bar plots for aggregate ratings by country
   - Product affinity by age group using heatmaps

5. **Insights & Observations**
   - India dominates in restaurant count and online delivery
   - Rating distribution shows left-skewed outliers
   - Product affinity varies significantly across age groups

---

## ⚠️ Challenges Faced

- **Missing values** in `Cuisines` column — handled by dropping due to low impact
- **Outliers** in `Average Cost for two`, `Votes`, and `Aggregate rating` — identified via descriptive stats
- **Encoding issues** — resolved using `'latin-1'` during CSV import

---

## 📊 Visualizations Included

- Pie charts (Top countries, cities, online delivery)
- Count plots (Rating color, city category, marital status)
- Clustered bar plots (Aggregate rating by country, occupation by gender)
- Heatmap (Product affinity by age group)

---

## 👥 Collaborators

Special thanks to:
- **Pranav Jaipurkar**
- **Chirag**
- **Sandhya**

for their guidance and contributions during the session.

---

## 📎 Next Steps

- Extend EDA to predictive modeling
- Share learnings via LinkedIn 
- Invite feedback and collaboration
