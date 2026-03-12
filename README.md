# crm-sales-analytics
# 📊 CRM Sales Analytics

A complete CRM sales analysis project combining **Python (Jupyter Notebook)** for data exploration and cleaning with a **Power BI** dashboard for interactive visualization.

---

## 📁 Repository Structure

```
crm-sales-analytics/
├── CRM-analysis.ipynb              # Python EDA & data cleaning notebook
├── Dashboard.pbix                  # Power BI interactive dashboard
├── data/
│   ├── accounts.csv                # Raw accounts data
│   ├── products.csv                # Products catalog
│   ├── sales_teams.csv             # Sales teams & regional offices
│   ├── sales_pipeline.csv          # Raw pipeline data
│   ├── accounts_cleaned.csv        # Cleaned accounts (output of notebook)
│   └── sales_pipeline_cleaned.csv  # Cleaned pipeline (output of notebook)
└── README.md
```

---

## 📌 Project Overview

This project analyzes a CRM sales dataset from Kaggle to uncover patterns in sales performance, agent productivity, product success, and regional distribution. The cleaned data feeds directly into a Power BI dashboard for business-level reporting.

---

## 🔍 Notebook — What's Covered

### 1. Data Import & Exploration
- Loads 4 datasets: Accounts, Products, Sales Teams, Sales Pipeline
- Inspects shape, dtypes, and null counts per dataframe

### 2. Data Cleaning
- Identifies missing values across all datasets
- Drops uninformative columns (`subsidiary_of`)
- Fills nulls in `close_value` with `0`, text fields with `'Unknown'`
- Exports cleaned CSVs for Power BI consumption

### 3. Analysis & Visualizations

| Analysis | Key Finding |
|---|---|
| Deal stage distribution | 4,238 Won · 2,473 Lost · 1,589 Engaging |
| Top agents by won deals | Darcel Schlecht — 349 won deals |
| Top agents by revenue | Darcel Schlecht — $1,153,214 total |
| Won deals by region | Central (38%) › West › East |
| Top companies | Kan-code — 115 won deals, $341,455 |
| Top sectors | Retail — 799 won deals, $1,867,528 |
| Top products by volume | GTX Basic leads in deal count |
| Top products by revenue | GTXPro, GTX Plus Pro, MG Advanced |
| Monthly trend | Peak in June 2017 at $1,338,466 |

### 4. Final Conclusions
- **Target sectors:** Retail, Technology, Software, Medical
- **High volume ≠ high value:** GTX Basic leads in deal count but GTXPro leads in revenue
- **Central office** is the strongest performing region
- **Sales are volatile** month-to-month — pipeline consistency needs improvement

---

## 📊 Power BI Dashboard — Pages

| Page | Content |
|---|---|
| **Revenue Overview** | Total revenue card · Revenue by product · Revenue trend over time · Sector & account filters |
| **Team Performance** | Revenue vs Target KPI · Deal details table · Deal stage pie chart · Agent & product filters |
| **Comparative Analysis** | Active agents card · Revenue by agent · Target vs Won revenue · Deal stage breakdown · Region & manager filters |



**Chahd**
📧 your-email@example.com
🔗 [LinkedIn](https://linkedin.com/in/your-profile)
