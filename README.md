# 🌍 Global Retail Expansion & Revenue Analysis

A strategic Tableau dashboard built to support **C-suite decision-making** — analyzing online retail transaction data to forecast revenue, identify high-value customers, evaluate geographic performance, and pinpoint optimal regions for global expansion.

[![Tableau Public](https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/josh.pardosi/viz/GlobalRetailExpansionRevenueAnalysis/Question4)

---

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/josh.pardosi/viz/GlobalRetailExpansionRevenueAnalysis/Question4)**

---

## 🎯 Project Overview

An online retail company is preparing for **international expansion** and needs data-driven answers to critical business questions. This project transforms transactional data into four focused analyses designed for the **CEO** and **CMO**, each addressing a specific strategic priority:

| # | Strategic Question | Stakeholder |
|---|-------------------|-------------|
| 1 | How is revenue trending, and what can we forecast? | CEO |
| 2 | Which countries (outside the UK) generate the most revenue? | CMO |
| 3 | Who are our highest-value customers to retain? | CMO |
| 4 | Where is global demand strongest for expansion? | CEO |

---

## 🔍 Key Insights & Findings

### 📈 1. Revenue Forecasting (CEO View)
- Monthly revenue trends across **2011** reveal clear **seasonal peaks**, with a sharp upward trajectory in Q4 — likely driven by holiday purchasing behavior.
- This seasonality pattern enables more accurate demand planning, staffing, and inventory management for future quarters.
- The data supports budgeting decisions around marketing spend timing and promotional campaigns.

### 🌐 2. Geographic Performance (CMO View)
- The **Top 10 revenue-generating countries** (excluding the UK home market) were identified and ranked.
- A critical comparison between **revenue volume** and **order quantity** reveals that some markets generate high revenue with fewer transactions (high average order value), while others rely on transaction volume.
- This distinction helps the CMO tailor market strategies — premium positioning vs. volume-driven growth.

### 💎 3. Customer Retention (CMO View)
- The **Top 10 highest-value customers** were identified based on cumulative spending.
- These customers represent a disproportionate share of total revenue, making them prime candidates for **VIP retention campaigns**, personalized offers, and loyalty programs.
- Losing even a single top-tier customer could meaningfully impact quarterly revenue targets.

### 🗺️ 4. Global Expansion Opportunities (CEO View)
- A geographic map visualization plots **product demand by units sold** across all countries in the dataset.
- Regions with the **highest organic demand** (without active marketing presence) represent the strongest candidates for market entry.
- This demand-first approach reduces expansion risk by prioritizing markets where customers are already buying.

---

## 🧹 Data Preparation

Before analysis, the dataset was cleaned to ensure accuracy:

- **Removed returns:** Filtered out all records with **negative quantities**, which represent returned or cancelled orders and would distort revenue calculations.
- **Removed invalid pricing:** Excluded records with **unit prices below $0**, which indicate data entry errors or system anomalies.

These steps ensured that all revenue figures and demand metrics reflect genuine, completed transactions.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau** | Data cleaning, transformation, and interactive dashboard development |
| **Online Retail Dataset** | Transactional data covering international e-commerce orders |

---

## 📁 Repository Structure

```
Global-Retail-Expansion-Revenue-Analysis/
├── README.md              # Project documentation
└── ...                    # Tableau workbook and data files
```

---

## 👤 About the Author

**Josh Peter Pardosi** — *Aspiring Data Analyst*

Computer Science undergraduate at Universitas Sumatera Utara (GPA: 3.68). Passionate about transforming raw data into actionable insights.

- **LinkedIn:** [Josh Peter Pardosi](https://www.linkedin.com/in/josh-peter-pardosi-44ab612aa/)
- **Email:** itsjoshpeter@gmail.com
