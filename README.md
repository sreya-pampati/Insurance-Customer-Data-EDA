
# 🧾 Insurance Customer Data EDA

This project performs **Exploratory Data Analysis (EDA)** on an insurance customer dataset. The goal is to uncover key patterns, trends, and insights that could support data-driven decision-making in customer segmentation, policy development, and business strategy.

## 📊 Project Objective

- Understand the distribution and relationships between customer attributes (age, gender, region, etc.)
- Identify trends in policy uptake and claim behavior
- Uncover potential factors influencing insurance purchases and renewals

## 📁 Dataset Description

The dataset typically includes the following fields:

- **Customer ID** – Unique identifier for each customer
- **Age** – Age of the customer
- **Gender** – Male or Female
- **Region** – Geographic location
- **Policy Type** – Type/category of insurance policy
- **Premium Amount** – Amount paid for the policy
- **Claims** – Whether a claim was made or not
- **Tenure** – How long the customer has been with the company

> *Note: Exact column names may vary based on the original dataset used.*

## 🧪 EDA Steps

1. **Data Cleaning**
   - Checked for missing/null values
   - Handled inconsistent data types
   - Removed duplicates

2. **Univariate Analysis**
   - Distribution of age, premium, tenure
   - Gender and region proportions
   - Most common policy types

3. **Bivariate Analysis**
   - Claims vs. Age
   - Premium vs. Tenure
   - Gender vs. Policy type

4. **Multivariate Analysis**
   - Correlation heatmap
   - Pairplots to observe relationships between numerical variables

5. **Key Insights**
   - High correlation between age and policy premium
   - Certain regions show higher claim rates
   - Male customers slightly dominate policy uptake

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook or Google Colab

## 📌 Conclusion

This analysis gives a better understanding of customer behavior, which can help:

- Target high-value customers
- Design customer-specific insurance plans
- Improve risk management strategies
