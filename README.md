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

## 📊 RFM Customer Segmentation & Pareto Analysis (Excel Project)

This project applies RFM (Recency, Frequency, Monetary) analysis to segment customers based on purchasing behavior and identify revenue concentration patterns.

🔹 Project Enhancements

In addition to basic RFM segmentation,I :

Performed a Pareto (80/20) analysis to identify the customers driving 80% of total revenue.

Analyzed how the 80% revenue group is distributed across different RFM segments using a Pivot Table.

Compared % Revenue vs % Customer Distribution by RFM segment to evaluate segment efficiency.

Identified revenue concentration risk and churn exposure.

🔹 Key Analytical Components

RFM scoring using percentile-based ranking

Customer segmentation using structured IFS logic

Pareto revenue classification (Top 80% vs Bottom 20%)

Pivot table analysis of revenue and customer share

Comparative chart: % Revenue vs % Total Customers by segment

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

###  RFM Segmentation
![RFM Segmentation Distribution]()

This chart shows the percentage distribution of customers across the RFM segments, highlighting retention strength and churn exposure.

---

###  Customer Distribution  
![Customer Segmentation Pivot Summary](RFM%20Segmentation.PNG)

This pivot table summarizes customer counts and percentage contribution per segment, supporting strategic marketing decisions.

---

###  RFM Scoring & Ranking Process  
![RFM Scoring and Ranking Process](RFM%20Scoring.PNG)

---

###  Parento Analysis 
![Parento_Analysis](Parento%20analysis.PNG)

This chart shows the parento distribution of customers, total revenue and cummulative % of revenue

---

###  Parento Segment 
![Parento Segment](Parento%20Segment.PNG)

This pivot table summarizes customer counts and percentage contribution per segment, on the Top 80% revenue and the remaining 20%

---

### 3️⃣ Revenue vs Customer  
![RFM Scoring and Ranking Process](Revenue%20vs%20customer.PNG)

This preview displays the total revenue % and total customer %, for better view of high segent and revenue

---

## 📈 Key Insights

26% of customers generate 80% of total revenue.

Revenue is highly concentrated among High-Potential and Champions segments.

At Risk customers represent significant churn danger.

Segment size does not always align with revenue contribution.

---

## Recommendations 

🎯 Protect Champions immediately — assign account managers, exclusive offers, VIP treatment; losing even a few hits revenue hard 

📈 Invest heavily in High-Potential — they're your largest segment with the most room to grow; targeted upsell campaigns can convert them to Champions 

⚠️ Launch a win-back campaign for At Risk — 674 in the bottom tier means revenue is leaking; use personalized discounts or re-engagement emails before they become Lost 

💎 Reward Loyal Customers more aggressively — they over-index on revenue; a loyalty tier upgrade program could push more into the top 80% 

🚫 Minimize spend on Lost Customers — redirect that budget to At Risk retention instead 📊 Focus 80% of your marketing budget on the 1,129 top customers — they are your business engine; retention beats acquisition here.

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
