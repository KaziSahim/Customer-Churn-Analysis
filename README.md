 # 🏦 Bank Customer Churn Analysis

 An end-to-end **Customer Churn Analytics project** focused on identifying customer attrition patterns, understanding customer behavior, and uncovering factors associated with churn using **Excel, SQL, and Power BI**.

 The project demonstrates a complete data analytics workflow — from data cleaning and SQL-based analysis to KPI development and interactive dashboard visualization.

---

 ## 📊 Project Overview

 Customer churn is a major challenge for banks because losing existing customers can result in:

 - Reduced revenue
- Increased customer acquisition costs
- Lower customer lifetime value
- Loss of long-term relationships

 This project analyzes customer demographics, financial characteristics, account activity, and product usage to identify **high-risk customer segments** and provide data-driven recommendations for improving customer retention.

---

 ## 🎯 Business Objectives

 The main objectives of this analysis are to:

 - Measure the overall **customer churn rate**.
- Identify customer segments with higher churn rates.
- Analyze the relationship between **credit score, age, balance, tenure, and churn**.
- Compare **active vs. inactive customer behavior**.
- Evaluate how the number of products used affects customer retention.
- Identify geographic regions with higher churn.
- Provide actionable recommendations to improve **customer retention and engagement**.

---

 ## ❓ Business Problem

 The bank wants to understand:

 > **Why are customers leaving, which customer segments are most at risk, and what actions can be taken to improve retention?**

 The analysis focuses on answering these questions through customer-level data and interactive business intelligence dashboards.

---

 ## 📂 Dataset

 The dataset contains information about **10,000+ bank customers**, including demographic, financial, and account activity attributes.

 ### Data Dictionary

 | Column | Description |
| --- | --- |
| `CustomerId` | Unique customer identifier |
| `CreditScore` | Customer credit score |
| `Geography` | Customer's country/region |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Tenure` | Number of years with the bank |
| `Balance` | Customer account balance |
| `NumOfProducts` | Number of banking products used |
| `HasCrCard` | Whether the customer has a credit card |
| `IsActiveMember` | Customer activity status |
| `EstimatedSalary` | Estimated annual salary |
| `Exited` | Customer churn status (`1 = Churned`, `0 = Retained`) |

---

 ## 🛠️ Tools & Technologies

 | Tool | Purpose |
| --- | --- |
| **Excel** | Data cleaning and preprocessing |
| **SQL** | Data analysis, segmentation, and KPI calculation |
| **Power BI** | Dashboard development and visualization |
| **GitHub** | Version control and project documentation |

---

 ## 📈 Key Performance Indicators

 The dashboard tracks important customer retention KPIs including:

 - **Total Customers**
- **Total Churned Customers**
- **Churn Rate**
- **Retention Rate**
- **Active Member Ratio**
- **Average Customer Balance**
- **Average Credit Score**
- **Customers at Risk**

 These KPIs provide a high-level view of customer health and churn performance.

---

 ## 🔍 Exploratory Analysis

 ### 👥 Customer Churn Analysis

 Customer churn was analyzed across different demographic and account characteristics to identify high-risk groups.

 Key dimensions analyzed include:

 - Age groups
- Gender
- Geography
- Credit score
- Tenure
- Account balance
- Product usage
- Customer activity

---

 ### 📦 Product Usage & Churn

 The relationship between the number of banking products and customer churn was analyzed.

 **Key Finding:**

 - Customers using fewer banking products showed different churn behavior compared with customers using multiple products.
- Product engagement can therefore be used as an important indicator when identifying customers who may require additional attention.

 **Business Impact:**

 The bank can use product usage patterns to:

 - Identify customers with low engagement.
- Develop targeted cross-selling strategies.
- Increase customer relationship depth.
- Improve retention through personalized product recommendations.

---

 ### 🟢 Active vs. Inactive Customers

 Customer activity status was compared against churn behavior.

 **Key Finding:**

 - Inactive members showed a significantly higher tendency to churn than active members.

 **Business Impact:**

 The bank can prioritize inactive customers for:

 - Personalized communication
- Engagement campaigns
- Product recommendations
- Loyalty programs
- Retention offers

---

 ### 🌍 Geographic Churn Analysis

 Customer churn was analyzed across different geographic regions.

 **Key Finding:**

 - Churn rates varied across regions, highlighting geographic segments that require closer investigation.

 **Business Impact:**

 Regional churn insights can help the bank:

 - Develop location-specific retention strategies.
- Identify regional service issues.
- Allocate customer retention resources more effectively.

---

 ### 💳 Credit Score & Financial Behavior

 Credit score, account balance, salary, and other financial characteristics were analyzed to understand their relationship with customer churn.

 This helps identify customer profiles that may require additional engagement or retention efforts.

---

 ## 📊 Power BI Dashboard

 An interactive Power BI dashboard was developed to provide a centralized view of customer churn and retention performance.

 ### Dashboard Includes

 - 👥 Total customer KPIs
- 📉 Churn and retention rate
- 🟢 Active vs. inactive customers
- 🌍 Geographic churn analysis
- 💳 Credit score analysis
- 💰 Customer balance analysis
- 📦 Product usage analysis
- 👤 Customer demographic segmentation

 ### Dashboard Preview

---

 ## 📌 Key Business Insights

 The analysis identified several important churn patterns:

 - **Inactive customers** showed a higher tendency to churn.
- Customer churn varied significantly across **geographic regions**.
- **Product usage** was associated with customer retention behavior.
- Customer **age and financial characteristics** provided useful segmentation opportunities.
- Customers with lower engagement can be prioritized for targeted retention campaigns.

---

 ## 💡 Business Recommendations

 Based on the analysis, the bank can consider:

 | Finding | Recommended Action |
| --- | --- |
| High churn among inactive customers | Launch targeted re-engagement campaigns |
| Geographic differences in churn | Develop region-specific retention strategies |
| Low product engagement | Introduce relevant cross-selling opportunities |
| High-risk customer segments | Create early-warning churn monitoring |
| Customer engagement gaps | Personalize communication and loyalty programs |

---

 ## 📊 Measuring Business Impact

 The effectiveness of retention strategies can be evaluated using before-and-after KPIs such as:

 | KPI | Before | After | Target |
| --- | --- | --- | --- |
| Churn Rate | Baseline | Measured after campaign | ↓ |
| Retention Rate | Baseline | Measured after campaign | ↑ |
| Active Member Ratio | Baseline | Measured after campaign | ↑ |
| Revenue at Risk | Baseline | Measured after campaign | ↓ |
| Product Adoption | Baseline | Measured after campaign | ↑ |

 > **Note:** Actual before/after business impact should only be reported after implementing and measuring the recommended strategies. The project itself identifies opportunities rather than claiming that these improvements were already achieved.

---

 ## 🚀 How to Run the Project

 ### 1\. Clone the Repository

```
git clone https://github.com/KaziSahim/E-commerce-Sales-Analysis.git
```

 > Update this repository URL to the dedicated Bank Customer Churn repository if you create one.

 ### 2\. Prepare the Dataset

 Import the customer dataset from the `/data` folder into your SQL database.

 ### 3\. Run SQL Analysis

 Open the SQL scripts from:

```
/sql
```

 Execute the queries to reproduce the KPI calculations and customer segmentation analysis.

 ### 4\. Open Power BI

 Open the Power BI file from:

```
/powerbi
```

 Refresh the data and explore the interactive dashboard.

---

 ## 📁 Recommended Project Structure

```
Bank-Customer-Churn-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── sql/
│   └── churn_analysis.sql
│
├── powerbi/
│   └── customer_churn_dashboard.pbix
│
├── images/
│   └── image1.png
│
└── README.md
```

---

 ## 🎓 Skills Demonstrated

 This project demonstrates practical skills in:

 - SQL Data Analysis
- Excel Data Cleaning
- Data Transformation
- Customer Segmentation
- KPI Development
- Churn Analysis
- Power BI Dashboard Development
- Business Intelligence
- Data Visualization
- Business Insight Generation
- Data-Driven Decision Making

---

 ## 👨‍💻 Author

 ### **Saim Qazi**

 Aspiring Data Analyst skilled in:

 - SQL
- Excel
- Power BI
- Python
- Data Visualization
- Business Analytics

 ### 🔗 Connect With Me

 - **GitHub:** https://github.com/KaziSahim
- **LinkedIn:** https://www.linkedin.com/in/saim-qazi-780a55415/
- **Email:** qazisaim121@gmail.com

---

 ## ⭐ Support

 If you find this project useful, consider giving the repository a **star ⭐** and exploring the analysis.

 **One important correction:** I left the repository URL in the run instructions marked for replacement because the GitHub URL you gave me is for your **E-commerce Sales Analysis**, not a Bank Customer Churn repository. You should create a separate churn repository rather than pointing recruiters to the wrong project.
