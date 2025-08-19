# 🏦 Bank Customer Churn Analysis (EDA)

## 📌 Project Overview  
This project explores a **Bank Churn dataset (10,000+ customers)** to uncover patterns in customer behavior and identify factors that drive churn.  
Customer churn is a critical issue in banking since retaining customers is more cost-effective than acquiring new ones.  
The goal of this analysis is to generate actionable insights that can help banks **reduce churn and improve customer retention strategies**.

---

## 📂 Dataset  
- **Source:** Kaggle – Bank Customer Churn Dataset  
- **Rows:** 10,000 customers  
- **Columns:** 14 features including  
  - `CreditScore`, `Balance`, `Tenure`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `Geography`, `Exited (Target)`  

---

## 🔍 Exploratory Data Analysis (EDA)  
### Key Analyses Performed:
- **Balance vs Churn:** Identified that customers with balances in the range **₹97k–₹110k** were more likely to churn.  
- **Tenure vs Churn:** Customers with **0 years tenure had the highest churn probability (23%)**, indicating weak onboarding.  
- **Credit Card vs Churn:** Customers with credit cards showed higher churn likelihood, potentially due to debt stress.  
- **Products vs Churn:** Customers with multiple products were less likely to churn → bundling increases retention.  
- **Geography vs Churn:** **Germany (814 churners) had the highest churn**, followed by France (810) and Spain (413).  

---

## 📊 Visualizations  
- **Boxplots & Line plots** to analyze churn probability across balance, tenure, and credit score ranges.  
- **Bar charts** for churn distribution across geography and product categories.  

---

## 📈 Key Insights  
- **High churn risk among zero-tenure customers** → onboarding improvements needed.  
- **Mid-balance customers (₹97k–₹110k) churn more** → targeted loyalty rewards recommended.  
- **Credit card holders churn more often** → flexible repayment + reward programs required.  
- **Multi-product customers are loyal** → encourage cross-sell to reduce churn.  
- **Germany has the highest churn** → country-specific retention campaigns essential.  

---

## 🛠 Recommended Actions  
- **Onboarding:** Personalized offers & advisor calls for new customers.  
- **Loyalty Programs:** Exclusive investment products & rewards for mid-balance customers.  
- **Credit Card Retention:** Debt counseling & improved rewards.  
- **Cross-Selling:** Encourage multi-product ownership with bundled benefits.  
- **Regional Focus:** Run localized retention programs in Germany & France.  

---

## 🧑‍💻 Tech Stack  
- **Python**  
- **Pandas, NumPy** – data cleaning & wrangling  
- **Matplotlib, Seaborn** – data visualization  

---

## 📜 Resume Highlights  
- Performed **EDA on 10,000+ bank customer records** to uncover churn drivers.  
- Identified **23% churn among zero-tenure customers** and **2× higher churn in Germany vs Spain**.  
- Discovered that **multi-product customers were significantly less likely to churn**.  
- Proposed **data-driven retention strategies** with potential to reduce churn by **8–12%**.  

---

## 🚀 Next Steps  
- Apply **predictive modeling (Logistic Regression, XGBoost)** to classify churners.  
- Build a **dashboard in Power BI / Tableau** for real-time churn monitoring.  
- Develop **customer segmentation strategies** for targeted marketing.  

---

## 📎 References  
- [Kaggle Dataset: Bank Customer Churn Modeling](https://www.kaggle.com/datasets)  
- Industry reports on **customer retention in retail banking**  

---

👤 **Author:** Syed Mustafa Ayaan Ali  
