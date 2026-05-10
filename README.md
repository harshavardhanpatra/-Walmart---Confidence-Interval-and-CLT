# Walmart Customer Purchase Behavior Analysis using CLT & Confidence Intervals

## 📌 Project Overview

This project is a complete business case study and statistical analysis of Walmart Black Friday sales data. The goal of the analysis was to understand customer purchase behavior and identify whether spending patterns differ across demographic groups such as gender, age, marital status, city category, and customer stay duration.

The project combines:

* Exploratory Data Analysis (EDA)
* Business Analytics
* Statistical Inference
* Central Limit Theorem (CLT)
* Confidence Interval Estimation
* Data Visualization
* Customer Segmentation

The analysis was performed on more than **550,000 customer transactions** collected during Walmart’s Black Friday sales event. 

---

# 🎯 Business Problem

Walmart’s management team wanted to analyze customer spending behavior to answer key business questions such as:

* Do male and female customers spend differently?
* Does marital status influence purchase behavior?
* Which customer segments contribute the most revenue?
* How can Walmart use statistical analysis to improve targeting and decision-making?

The project focuses on transforming raw transactional data into actionable business recommendations. 

---

# 📊 Dataset Information

The dataset contains transactional purchase records from Walmart Black Friday sales.

### Dataset Highlights

* Total Transactions: **550,068**
* Total Features: **10**
* Unique Customers: **5,891**
* Unique Products: **3,631**
* Dataset Type: Mixed categorical and numerical features

### Features Included

* User_ID
* Product_ID
* Gender
* Age
* Occupation
* City_Category
* Stay_In_Current_City_Years
* Marital_Status
* Product_Category
* Purchase Amount 

---

# 🛠️ Technologies & Libraries Used

## Programming & Analysis

* Python
* Pandas
* NumPy

## Visualization

* Matplotlib
* Seaborn

## Statistics

* Central Limit Theorem (CLT)
* Confidence Intervals
* Bootstrap Sampling
* Distribution Analysis

---

# 🔍 Analysis Performed

## 1. Data Cleaning & Preprocessing

* Converted categorical variables into category datatype
* Checked missing values
* Performed duplicate detection
* Conducted sanity checks for all features
* Optimized memory usage significantly

---

## 2. Exploratory Data Analysis (EDA)

### Univariate Analysis

* Purchase amount distribution
* Customer age distribution
* City category analysis
* Occupation analysis
* Product category analysis

### Bivariate Analysis

* Gender vs Purchase
* Age vs Purchase
* Marital Status vs Purchase
* City Category vs Purchase
* Stay Duration vs Purchase

### Outlier Detection

* Identified high-value purchase outliers
* Analyzed their business significance instead of blindly removing them

---

# 📈 Statistical Analysis

One of the major goals of this project was to apply the **Central Limit Theorem (CLT)** and construct **Confidence Intervals** to estimate population-level spending behavior.

The project includes:

* Bootstrap sampling
* Sample size experimentation
* CLT visualization
* Confidence interval comparison
* Statistical interpretation of overlap vs non-overlap

Sample sizes tested:

* 100
* 1,000
* 5,000
* 50,000

Confidence levels used:

* 90%
* 95%
* 99% 

---

# 📌 Key Business Insights

## 👨 Gender Analysis

* Male customers contributed significantly more total revenue because of higher transaction volume.
* Average spending per transaction was only slightly higher for males.
* As sample size increased, confidence intervals clearly separated, showing statistically meaningful spending differences between genders. 

### Business Recommendation

* Walmart can design gender-specific marketing campaigns and premium product targeting strategies.

---

## 💍 Marital Status Analysis

* Married and unmarried customers showed almost identical spending behavior.
* Confidence intervals overlapped across all sample sizes.
* Marital status had minimal impact on purchase amount. 

### Business Recommendation

* Walmart should avoid heavily segmenting campaigns based on marital status.

---

## 👥 Age Group Analysis

* The 26–35 age group generated the highest revenue contribution.
* Spending behavior across age groups remained relatively consistent.
* Older groups showed slightly higher average purchases, but differences were not practically significant. 

### Business Recommendation

* Walmart should prioritize engagement strategies for the 26–35 segment while maintaining broad targeting across age groups.

---

# 📊 Visualization Highlights

The project contains professionally designed visualizations including:

* Histograms
* KDE Plots
* Boxplots
* Donut Charts
* Stacked Revenue Charts
* Confidence Interval Curves
* CLT Sampling Distributions

These visualizations were built not only for analysis but also for business storytelling and presentation clarity.

---

# 🚀 Learning Outcomes

This project helped strengthen practical understanding of:

* Statistical inference in real-world business problems
* Central Limit Theorem implementation
* Confidence interval interpretation
* Customer segmentation analysis
* Business storytelling with data
* Data visualization best practices
* Large-scale exploratory data analysis

---

# 📂 Repository Structure

* `Walmart_CLT_Case_Study.ipynb` → Full notebook with analysis and visualizations
* `wallmart_final_project_submission_Harsha.pdf` → Complete business case study report
* `README.md` → Project documentation

---

# ✅ Conclusion

This project demonstrates how statistical analysis and exploratory data analysis can be combined to solve real business problems. Instead of only focusing on charts and descriptive statistics, the study connects data findings with strategic business decisions that Walmart can leverage for customer targeting, pricing, and marketing optimization.

The project sits at the intersection of:

* Data Analytics
* Business Intelligence
* Statistical Modeling
* Data Storytelling
* Customer Behavior Analysis

---

# 👨‍💻 Author

**Harshavardhan Patra**
Aspiring Data Analyst | AI Engineer | Business Analytics Student
