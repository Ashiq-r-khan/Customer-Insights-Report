# 🛍️ Customer Insights Report – Retail Data Analysis with Python

A comprehensive data analytics project exploring customer behavior in the retail fashion sector. This project applies statistical techniques, data preprocessing, exploratory data analysis, and modeling to extract actionable business insights.

---

## 📌 Project Objectives

- Understand customer purchasing behavior across demographics, membership tiers, and product categories  
- Detect and handle outliers in key variables (income, spending, item counts)  
- Perform hypothesis testing to evaluate behavioral assumptions  
- Build a linear regression model to predict customer spending  
- Deliver strategic insights for improving eCommerce personalization and segmentation  

---

## 📂 Project Structure


---

## 🧰 Technologies & Libraries Used

- Python 3.x  
- pandas – Data manipulation  
- numpy – Numerical operations  
- seaborn & matplotlib – Data visualization  
- statsmodels – Statistical modeling  
- scipy – Hypothesis testing  

---

## 🔍 Key Analysis Steps

### ✅ 1. Data Quality Assessment
- Verified data types and integrity  
- No missing or duplicate records  
- Encoded categorical variables (`Gender`, `Membership`)  

### 📊 2. Exploratory Data Analysis (EDA)
- Visualized data distributions with histograms, boxplots, and bar charts  
- Analyzed purchase behavior by gender, membership, and product category  
- Heatmaps for correlation analysis  

### 🚨 3. Outlier Handling
- Applied IQR and percentile capping  
- Preserved high-value customers for insight  

### 🧪 4. Statistical Hypothesis Testing
- **Gender vs Returned:** No significant relationship (Chi-Square Test)  
- **Spending by Gender:** No significant difference (Welch’s T-Test)  
- **Spending by Membership:** No significant difference (One-Way ANOVA)  

### 📈 5. Predictive Modeling
- Multiple Linear Regression to predict `AmountSpent_Capped`  
- Features: Age, Annual Income, Items Purchased, Gender, Membership  
- R² = 0.011 → Low predictive power  
- Gender and Membership showed small but statistically significant effects  

---

## 📌 Insights & Recommendations

- Age and income are weak predictors of customer spending  
- Outlier customers (e.g., high spenders) are important and should be retained  
- Strong case for deeper customer segmentation via clustering  
- Top-selling categories: Bottoms, Traditional Wear, Accessories  
- Promote digital payments (bKash, Nagad, Debit Cards)  
- Consider revisiting membership benefits to better differentiate tiers  
- Gender-neutral approach to promotions is appropriate based on the data  

---

## 📥 Dataset

A simulated fashion retail dataset containing:

- Customer demographics  
- Purchase behavior  
- Return status  
- Satisfaction ratings  

> 📁 `retail_fashion_dataset.csv` is included for analysis.

---

## 📄 License

This project is provided for **educational and analytical purposes**. Please cite appropriately if reused or adapted.

---

## 🙌 Acknowledgments

Thanks to the open-source community and the creators of Python libraries that make such analytical work possible.

---

