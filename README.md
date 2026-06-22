# 📊 Customer Churn Analytics Project

An end-to-end Data Analytics and Machine Learning project focused on understanding customer churn behavior and identifying key factors that drive customer attrition.

The project combines **Python**, **Statistical Analysis**, **Machine Learning**, and an **interactive Power BI dashboard** to generate actionable business insights.

---

## 🚀 Project Overview

Customer churn is one of the most important business challenges for subscription-based companies.

In this project, I analyzed customer demographics, contract information, service usage, and financial metrics to:

- Identify the main drivers of churn
- Segment customers into risk groups
- Build a predictive churn model
- Design an executive Power BI dashboard for business decision-making

---

## 📂 Project Structure

```
customer-churn-analytics-project/
│
├── data/
│   ├── Telco_customer_churn.xlsx
│   └── customer_churn_dashboard.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_statistical_analysis.ipynb
│   ├── 04_predictive_modeling.ipynb
│   ├── 05_customer_segmentation.ipynb
│   └── 07_powerbi_preparation.ipynb
│
├── dashboard/
│   └── Customer_Churn_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
├── README.md
└── requirements.txt
```

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Power BI
- Jupyter Notebook
- OpenPyXL

---

# 📈 Exploratory Data Analysis

The exploratory analysis revealed several important patterns:

- Customers on **month-to-month contracts** churn significantly more than those on long-term contracts.
- **Fiber optic** customers exhibit higher churn rates than DSL customers.
- Customers paying through **electronic checks** are more likely to churn.
- Lack of **Tech Support** and **Online Security** services is associated with increased churn.
- Customers with shorter tenure tend to leave at much higher rates.

---

# 🤖 Machine Learning

## Customer Segmentation

K-Means clustering was used to divide customers into three distinct risk segments:

- 🟢 Low Risk
- 🟡 Medium Risk
- 🔴 High Risk

The segmentation enables targeted retention strategies and customer prioritization.

---

## Churn Prediction Model

A Logistic Regression model was trained to predict customer churn.

### Model Performance

| Metric | Score |
|----------|--------|
| Accuracy | **90.97%** |
| Precision (Churn) | **84%** |
| Recall (Churn) | **82%** |
| F1 Score | **83%** |

---

# 📊 Power BI Dashboard

The interactive dashboard provides executives with a comprehensive overview of customer churn and business performance.

### Dashboard Highlights

- KPI summary cards
- Customer churn distribution
- Churn by contract type
- Churn by internet service
- Churn by payment method
- Risk cluster distribution
- Top churn reasons
- Machine learning model performance
- Business recommendations

---

# 💡 Key Business Insights

- Month-to-month contracts have the highest churn rate.
- Fiber optic customers are considerably more likely to churn.
- Electronic check payment methods are strongly associated with customer attrition.
- High-risk customer segments exhibit substantially higher churn rates than low-risk groups.
- Customer tenure is one of the strongest indicators of retention.

---

# 📋 Business Recommendations

- Encourage migration to long-term contracts.
- Promote Tech Support and Online Security services.
- Prioritize retention efforts for high-risk customers.
- Improve competitive pricing and customer value propositions.
- Develop proactive interventions based on predictive analytics.

---

# 📦 Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

# 📚 Dataset

This project uses the **IBM Telco Customer Churn** dataset for educational and portfolio purposes.

---

# 👤 Author

**Mohamad Younes**

- Data Analytics Portfolio Project
- Built using Python, Machine Learning, and Power BI
