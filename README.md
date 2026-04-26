# 🛍️ Customer Shopping Behavior Analysis
### End-to-End Data Analytics Project | Python · SQL · Power BI

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange?style=flat&logo=mysql)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat&logo=powerbi)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 📌 Project Overview

This project simulates a **corporate-grade, end-to-end data analytics workflow** on retail customer shopping data. The goal is to uncover actionable insights around customer behavior, purchase patterns, loyalty segments, and revenue drivers — and communicate them through interactive dashboards and a stakeholder-ready report.

The project mirrors the real responsibilities of a professional Data Analyst, covering every stage from raw data ingestion to final business recommendations.

---

## 🎯 Business Problem

Retail businesses often struggle to understand **who their customers are**, **what drives their purchases**, and **how to retain high-value customers**. This project addresses the following key business questions:

- Which customer segments generate the most revenue?
- What are the top-performing product categories by season?
- How does loyalty status affect purchase frequency and spend?
- What payment and shipping preferences dominate across demographics?
- Which factors most influence repeat purchases?

---

## 🗂️ Project Workflow

```
Raw Data (CSV)
     │
     ▼
Python (EDA & Data Cleaning)
     │
     ▼
SQL Database (Business Queries & Analysis)
     │
     ▼
Power BI (Interactive Dashboard)
     │
     ▼
Report & Presentation (Stakeholder Deliverables)
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** (Pandas, Matplotlib, Seaborn) | Data cleaning, EDA, DB connection |
| **SQL** (MySQL / PostgreSQL) | Business querying, segmentation analysis |
| **Power BI** | Interactive dashboard & data visualization |
| **Google Colab** | Analysis environment |
| **Gamma AI** | Presentation creation |

---

## 🔍 Key Analytical Steps

### 1. 🐍 Data Preparation & EDA (Python)
- Loaded and inspected raw retail CSV data
- Handled missing values, data types, and outliers
- Performed exploratory analysis on customer demographics, purchase amounts, categories, seasons, and loyalty tiers
- Visualized distributions and correlations using Matplotlib and Seaborn
- Connected Python to SQL database and loaded cleaned data

### 2. 🗄️ Data Analysis (SQL)
- Simulated business transactions using structured queries
- Analyzed customer segments by spend, frequency, and loyalty
- Identified top revenue-driving categories and seasonal trends
- Answered stakeholder-defined business questions using aggregations, JOINs, and window functions

### 3. 📊 Dashboard & Visualization (Power BI)
- Connected Power BI directly to SQL database
- Built an interactive dashboard with slicers for age, gender, category, and season
- Visualized KPIs: total revenue, average order value, customer count, top segments
- Enabled drill-down analysis for stakeholders

### 4. 📝 Report & Presentation
- Wrote a structured project report summarizing methodology, findings, and recommendations
- Built a clean stakeholder presentation with key insights and next steps

---

## 📈 Key Insights

- 🏆 **Clothing** is the highest revenue-generating category across all seasons
- 👥 **Male customers aged 25–45** account for the largest purchase volume
- 💳 Customers using **promo codes** have significantly higher average order values
- 🔄 **Subscription-based (loyal) customers** purchase 2x more frequently than non-subscribers
- 🚚 **Free shipping** is the most preferred shipping method and correlates with higher cart sizes

---

## 🚀 How to Run This Project

### Prerequisites
```bash
pip install pandas matplotlib seaborn sqlalchemy pymysql jupyter
```

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

2. **Run the Python notebook**
   - Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter
   - Execute cells for data cleaning, EDA, and DB loading

3. **Run SQL queries**
   - Set up a MySQL or PostgreSQL database
   - Execute `customer_behavior_sql_queries.sql` to answer business questions

4. **Open the Power BI Dashboard**
   - Open `customer_behavior_dashboard.pbix` in Power BI Desktop
   - Reconnect to your local SQL database if prompted

---

## 📄 Reports & Deliverables

| Deliverable | File |
|-------------|------|
| Project Report | `customer shopping behavior analysis.pdf` |
| Stakeholder Presentation | `Customer-Shopping-Behavior-Analysis.pptx` |
| Business Problem Statement | `Business Problem Document.pdf` |

---

## 🤝 Connect With Me

If you found this project helpful, feel free to connect:
- 📧 **Email:** avisaini764@gmail.com

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---
