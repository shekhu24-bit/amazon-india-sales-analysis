# 🛒 Amazon India Sales Analysis
### Fashion & Apparel E-Commerce | Apr – Jun 2022

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📌 Project Overview

This project analyzes **1,28,942 Amazon India orders** worth **₹7.85 Crore** from April to June 2022.

Built an end-to-end data analytics pipeline:
- **Python (Pandas, NumPy)** for data cleaning & exploratory data analysis
- **ABC Classification** to identify high-revenue SKUs
- **Power BI** for an interactive 5-page dashboard
- **DAX** for custom KPI measures

---

## 🎯 Key Business Insights

| Insight | Finding |
|---------|---------|
| 💰 Total Revenue | ₹7.85 Crore (Apr–Jun 2022) |
| 📦 Total Orders | 1,28,942 orders |
| 🏆 Top Category | Set (₹3.9 Cr = 50% of revenue) |
| 🔍 ABC Analysis | 1,324 Class-A SKUs generate 70% revenue |
| ❌ Cancellation Rate | 14.21% overall |
| 🚚 Amazon vs Merchant | Amazon FBA: 12.79% vs Merchant: 17.47% cancellation |
| 🗺️ Top State | Maharashtra (₹1.33 Cr) |
| 🏙️ Top City | Bengaluru (₹68.5 Lakh) |
| 🏢 B2B vs B2C | 99.25% B2C business |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning, EDA, ABC Classification |
| Jupyter Notebook | Analysis environment |
| Power BI Desktop | Interactive dashboard |
| DAX | Custom KPI measures (AOV, Fulfillment Rate %) |

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| 1️⃣ Cover | Project overview & key stats |
| 2️⃣ Executive Summary | KPI cards, monthly revenue trend, category revenue, order outcomes |
| 3️⃣ Category & Product | ABC Treemap, Top 10 SKUs by revenue, category performance |
| 4️⃣ Geographic Analysis | State & city-wise revenue map, cancellation hotspots |
| 5️⃣ Fulfillment & Cancellation | Amazon vs Merchant, cancellation trends, B2B vs B2C split |

---

## 📁 Project Structure

```
amazon-india-sales-analysis/
│
├── Amazon_Sales_Analysis.ipynb     ← Python EDA & ABC Analysis
├── Amazon_Sales_Dashboard.pbix     ← Power BI Dashboard (5 pages)
├── README.md                       ← Project documentation
│
├── data/
│   ├── powerbi_main_data.csv       ← Main cleaned transactions
│   ├── powerbi_category_summary.csv
│   ├── powerbi_state_summary.csv
│   └── sku_abc_classification.csv  ← ABC classified SKUs
│
└── screenshots/
    ├── 01_cover.png
    ├── 02_executive_summary.png
    ├── 03_category_product.png
    ├── 04_geographic_analysis.png
    └── 05_fulfillment_analysis.png
```

---

## 📈 Analysis Workflow

```
Raw Data (1,28,942 rows - Amazon Sale Report.csv)
                    ↓
        Python Data Cleaning (Pandas)
        - Removed nulls & duplicates
        - Created Revenue, Month, Order_Outcome columns
                    ↓
        Exploratory Data Analysis (EDA)
        - Monthly trends, Category analysis
        - State/City revenue distribution
        - Fulfillment & Cancellation analysis
                    ↓
        ABC Classification (SKU Level)
        - Class A: 1,324 SKUs → 70% revenue
        - Class B: 1,770 SKUs → 20% revenue
        - Class C: 4,063 SKUs → 10% revenue
                    ↓
        5 CSV Files Exported for Power BI
                    ↓
        Power BI Dashboard (5 Interactive Pages)
```

---

## 🔍 Dataset

- **Source:** [Amazon Sale Report - Kaggle](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)
- **Period:** April – June 2022
- **Rows:** 1,28,942 orders
- **Categories:** 9 (Kurta, Set, Western Dress, Top, Blouse, Bottom, Saree, Ethnic Dress, Dupatta)
- **Coverage:** Pan-India (28+ states, 100+ cities)

---

## 👤 Author

**Shekhar Tanwar**
MBA Finance & Business Analytics
Maharshi Dayanand University, Rohtak
📧 shekhartnwr28@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)

