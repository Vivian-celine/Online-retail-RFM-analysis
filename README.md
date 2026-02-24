## 📊 Online Retail RFM Analysis
📌 Internship Project – Elevvo Pathways

This project analyzes customer purchasing behavior using RFM (Recency, Frequency, Monetary) Analysis.
Customers were scored based on their activity and segmented into groups to support data-driven marketing strategies.

---

```
online-retail-rfm-analysis/
│
├── README.md
│
├── data/
│   └── online_retail_raw.xlsx
│
├── cleaned_data/
│   └── online_retail_cleaned.xlsx
│
├── images/
│   ├── rfm_distribution_chart.png
│   ├── segmentation_pivot_table.png
│   ├── rfm_scoring_process.png
│
└── docs/
    └── marketing_strategies_summary.pdf
```

---
## 🎯 Objective

Analyze customer behavior using Recency, Frequency, and Monetary metrics

Assign scores to each customer

Group similar customers using RFM segmentation

Suggest simple marketing strategies for each customer segment

---

## 📂 Dataset Overview

Initial dataset: 941,910 rows × 8 columns

After cleaning: 392,733 rows × 10 columns

Dataset type: Online Retail Transactions

---

## 🧹 Data Cleaning Process

The following steps were performed using Excel Power Query:

Imported dataset into Power Query

Removed duplicates based on Customer_ID

Removed blank rows

Rounded Unit Price to 2 decimal places

Extracted date from DateTime column

Created Revenue column (Quantity × Unit Price)

Filtered out:

Negative quantities where Invoice number starts with "C" (Cancelled transactions)

Rows where Stock Code = Bank Charges, Postage, Manual

---

## 📊 RFM Analysis Process

Using Pivot Tables:

Extracted:

Max Purchase Date

Distinct Invoice Count

Total Revenue

Then:

Calculated:

Recency

Frequency

Monetary

Ranked customers

Generated RFM Scores (1–10 scale)

Conducted segmentation using Excel formulas

Visualized results using Pivot Charts

---

## 🧩 Customer Segments

Customers were grouped into:

🏆 Champions

💎 Loyal Customers

🚀 High-Potential

⚠ At Risk

❌ Lost Customers

🌱 Others

---

## 📊 Dashboard Preview  

### 1️⃣ RFM Segmentation Distribution  
![RFM Segmentation Distribution](RFM.%20Distribution%20Chart.PNG)

This chart shows the percentage distribution of customers across the RFM segments, highlighting retention strength and churn exposure.

---

### 2️⃣ Customer Segmentation Pivot Summary  
![Customer Segmentation Pivot Summary](RFM.20Segmentation.PNG)

This pivot table summarizes customer counts and percentage contribution per segment, supporting strategic marketing decisions.

---

### 3️⃣ RFM Scoring & Ranking Process  
![RFM Scoring and Ranking Process](RFM.%20Scoring.PNG)

This preview displays the ranking and scoring logic used to generate Recency, Frequency, and Monetary scores before segmentation.

---

## 📈 Key Insights

~30% of customers are Champions & Loyal, forming a strong revenue base

Over 30% show churn signals (Lost + At Risk)

High-Potential customers present growth opportunity

A large "Others" segment suggests room for deeper behavioral targeting

---

## 💡 Marketing Recommendations Segment Strategy
Champions: VIP rewards, referrals, upselling
Loyal: Personalized offers, loyalty strengthening
High-Potential:	Increase frequency via targeted promotions
At Risk:	Re-engagement campaigns
Lost:	Win-back campaigns
Others:	Encourage repeat purchases

---

## 🛠 Tools Used

Microsoft Excel

Excel Power Query

Pivot Tables

Excel Formulas (RANK, IFS, Percentile)

---

## 🚀 Project Outcome

This project demonstrates practical application of:

Data Cleaning

Customer Segmentation

Behavioral Analysis

Business Strategy Translation
