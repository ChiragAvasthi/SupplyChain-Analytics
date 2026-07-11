# 🚚 Supply Chain Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-informational?style=flat&logo=postgresql)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow?style=flat&logo=powerbi)
![License](https://img.shields.io/badge/License-MIT-success?style=flat)

![Executive Overview](Dashboard%20Screenshots/1_Executive_Overview.png)

## 📑 Table of Contents
- [Project Overview](#-project-overview)
- [Business Objectives](#-business-objectives)
- [Tools & Technologies](#️-tools--technologies)
- [Prerequisites & Installation](#️-prerequisites--installation)
- [Usage](#-usage)
- [Dashboard Pages](#-dashboard-pages)
- [Key Insights](#-key-insights)
- [Project Workflow](#-project-workflow)
- [Project Structure](#-project-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Author](#-author)

---

## 📌 Project Overview

This End-to-End Supply Chain Analytics project analyzes inventory performance, supplier efficiency, logistics operations, and profitability using Python, SQL, and Power BI.

The project transforms raw supply chain data into actionable business insights through data cleaning, exploratory data analysis (EDA), SQL analysis, and interactive dashboards.

---

## 🎯 Business Objectives

- Analyze inventory and stock performance
- Evaluate supplier productivity and quality
- Monitor shipping costs and logistics efficiency
- Identify product defect trends
- Track profitability across product categories
- Support data-driven business decisions

---

## 🛠️ Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- PostgreSQL (SQL)
- Power BI
- Excel

---

## ⚙️ Prerequisites & Installation

To run the Python scripts and SQL analysis locally, ensure you have the following installed:
- **Python 3.x**
- **PostgreSQL** (or another compatible SQL database)
- **Power BI Desktop** (to view the `.pbix` file)

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Supply-Chain-Analytics-Dashboard.git
   cd Supply-Chain-Analytics-Dashboard
   ```

2. **Install Python dependencies:**
   It is recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

---

## 💻 Usage

- **Exploratory Data Analysis:** Open `Python/supply_chain_eda.ipynb` using Jupyter Notebook or JupyterLab to view the data cleaning and EDA steps.
- **SQL Analysis:** Import `Dataset/supply_chain_clean_data.csv` into your PostgreSQL database using the schema defined at the top of `SQL/supply_chain_analysis.sql`, and execute the analytical queries within that script.
- **Power BI Dashboard:** Open `Power BI/Supply_Chain_Analytics.pbix` in Power BI Desktop to interact with the visualizations.

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

- Revenue Analysis
- Product Performance
- Supplier Performance
- Shipping Cost Analysis
- Defect Rate Monitoring

![Executive Overview](Dashboard%20Screenshots/1_Executive_Overview.png)

---

### 2️⃣ Inventory & Supplier Analysis

- Stock Level Analysis
- Production Volume Tracking
- Supplier Performance Evaluation
- Quality Inspection Analysis
- Defect Rate Assessment

![Inventory & Supplier Analysis](Dashboard%20Screenshots/2_Inventory_Supplier_Analysis.png)

---

### 3️⃣ Logistics & Profitability Analysis

- Transportation Cost Analysis
- Shipping Time Analysis
- Lead Time Evaluation
- Profit Margin Analysis
- Logistics Performance Monitoring

![Logistics & Profitability Analysis](Dashboard%20Screenshots/3_Logistics_Profitability_Analysis.png)

---

### 4️⃣ Business Insights & Recommendations

- Executive Summary
- Key Findings
- Strategic Recommendations
- Business Improvement Opportunities

![Business Insights](Dashboard%20Screenshots/4_Business_Insights.png)

---

## 📈 Key Insights

- Skincare products generated the highest revenue.
- Supplier 1 contributed the highest overall revenue.
- Haircare products maintained the highest inventory levels.
- Supplier 2 achieved the highest production volume.
- Supplier 5 recorded the highest defect rate.
- Air transportation incurred the highest shipping cost.
- Cosmetics products delivered the highest profit margin.

---

## 🔄 Project Workflow

```text
Raw Data
    ↓
Data Cleaning (Python)
    ↓
Exploratory Data Analysis (EDA)
    ↓
Feature Engineering
    ↓
SQL Analysis (PostgreSQL)
    ↓
Power BI Dashboard Development
    ↓
Business Insights & Recommendations
```

---

## 📁 Project Structure

```text
Supply-Chain-Analytics-Dashboard
│
├── Dataset
│   ├── supply_chain_data.csv
│   └── supply_chain_clean_data.csv
│
├── Python
│   └── supply_chain_eda.ipynb
│
├── SQL
│   └── supply_chain_analysis.sql
│
├── Power BI
│   └── Supply_Chain_Analytics.pbix
│
├── Dashboard Screenshots
│   ├── 1_Executive_Overview.png
│   ├── 2_Inventory_Supplier_Analysis.png
│   ├── 3_Logistics_Profitability_Analysis.png
│   └── 4_Business_Insights.png
│
└── README.md
```

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Querying
- Data Visualization
- Dashboard Development
- Business Intelligence
- Supply Chain Analytics
- KPI Analysis
- Data Storytelling

---

## 👤 Author

**Chirag Avasthi**

Aspiring Data Analyst | SQL | Power BI | Python | Excel | Business Intelligence

---

### ⭐ If you found this project useful, consider giving it a star.
