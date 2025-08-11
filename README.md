 Walmart Purchase Behavior Analysis
📌 Project Overview
This project analyzes Walmart customer purchase patterns using demographic and transactional data. The objective is to explore purchase trends, understand customer segments, and provide actionable business recommendations.

🎯 Objective
Perform Exploratory Data Analysis (EDA) on Walmart purchase data.

Identify demographic influences on spending.

Use statistical methods (Confidence Intervals, CLT) to validate insights.

Provide business recommendations for marketing and inventory strategy.

📂 Dataset
The dataset includes customer purchase records with details like:

User demographics: Gender, Age, Occupation, Marital Status, City Category, Years in Current City

Product details: Product Category, Product ID

Transaction amount: Purchase value in INR

📊 Shape: 550,068 rows × 10 columns
📌 No missing values detected

🛠 Tools & Libraries
Python: pandas, numpy, matplotlib, seaborn, scipy

Jupyter Notebook / Google Colab

Statistical Analysis: t-tests, CLT, confidence intervals

🔍 EDA Highlights
1️⃣ Univariate Analysis
Majority customers: Males (~75%)

Most active age group: 26–35 years

City Category B dominates customer base

Purchase distribution: Right-skewed

2️⃣ Bivariate Analysis
Slightly higher average spending by females

Unmarried customers spend more than married customers

Age 26–35 is top-spending group

3️⃣ Correlation & Outliers
Weak correlations between demographics and purchase amount

2,677 purchase outliers detected via IQR method

📈 Statistical Insights (CLT & Confidence Intervals)
Gender-wise CI shows slight spending difference (Females > Males)

Age group differences significant between 26–35 vs 0–17

Unmarried customers likely to make impulsive purchases

💡 Business Recommendations
Target 26–45 Age Group with premium/luxury products.

Female-focused promotions to increase engagement.

City B should be prioritized for marketing and stock allocation.

Personalize campaigns by marital status (unmarried: lifestyle/travel; married: family bundles).

📊 Visualizations
Gender, Age, City distribution plots

Purchase amount histograms & boxplots

Correlation heatmap

Confidence interval bar charts
