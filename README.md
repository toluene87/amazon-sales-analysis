# 🛒 Amazon E-Commerce Sales Analysis

## Project Overview

This project analyzes **128,975 real Amazon India orders** from 2022 to uncover revenue trends, category performance, regional insights, and customer behavior patterns — enabling data-driven decisions for business growth and operational improvement.

The analysis was conducted entirely in Python using Pandas for data manipulation and Matplotlib/Seaborn for visualization.

---

## 🛠️ Tools Used

- **Python** — Core analysis language
- **Pandas** — Data loading, cleaning, and analysis
- **Matplotlib & Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive analysis environment

---

## 📁 Dataset

| Property | Detail |
|---|---|
| Total Records | 128,975 orders |
| Cleaned Records | 121,180 orders |
| Total Columns | 24 columns |
| Period Covered | March — June 2022 |
| Currency | Indian Rupees (₹) |
| Source | Real Amazon India sales data |

**Key columns used:**
- `Order ID`, `Date`, `Status`
- `Category`, `Size`, `Quantity`, `Amount`
- `City`, `State`
- `B2B` — whether the order was a business or consumer purchase
- `Fulfilment` — Amazon vs Merchant fulfilled

Dataset not included due to file size. Download the original from Kaggle: search "Amazon Sale Report" on kaggle.com

---

## 🔍 Analysis & Key Findings

### Analysis 1 — Overall Sales Overview
| Metric | Value |
|---|---|
| Total Unique Orders | 113,030 |
| Total Revenue | ₹78,592,678.30 |
| Average Order Value | ₹648.56 |
| Total Units Sold | 116,482 |

Nearly ₹79 million in revenue across 113,000 orders — establishing a strong baseline for deeper analysis.

### Analysis 2 — Revenue by Category
| Category | Total Revenue |
|---|---|
| Set | ₹39,204,124.03 |
| Kurta | ₹21,299,546.70 |
| Western Dress | ₹11,216,072.69 |
| Top | ₹5,347,792.30 |
| Dupatta | ₹915.00 |

Sets and Kurtas together account for **77% of total revenue**. The business is heavily concentrated in just 2 categories — a significant risk if either underperforms. Dupatta generates virtually no revenue and may not justify continued inventory investment.

### Analysis 3 — Monthly Sales Trend
| Month | Revenue |
|---|---|
| March | ₹101,683.85 |
| April | ₹28,838,708.32 |
| May | ₹26,226,476.75 |
| June | ₹23,425,809.38 |

Revenue peaked in April and has declined consistently month on month. March appears to be an incomplete month of data. The downward trend from April to June suggests possible seasonal effects or reduced marketing effectiveness heading into summer.

### Analysis 4 — Order Status Breakdown
| Status | Orders | Percentage |
|---|---|---|
| Shipped | 77,596 | 64.03% |
| Delivered | 28,761 | 23.73% |
| Cancelled | 10,766 | 8.88% |
| Returned | 1,950 | 1.61% |

An **8.88% cancellation rate** represents nearly 11,000 lost orders. Combined with only 23.73% of orders confirmed as delivered, there is a clear fulfillment tracking and customer communication gap that is likely hurting both revenue and customer trust.

### Analysis 5 — Top 10 States by Revenue
| State | Total Revenue |
|---|---|
| Maharashtra | ₹13,335,534.14 |
| Karnataka | ₹10,481,114.37 |
| Telangana | ₹6,916,615.65 |
| Uttar Pradesh | ₹6,816,642.08 |
| Tamil Nadu | ₹6,515,650.11 |
| Delhi | ₹4,235,215.97 |
| Kerala | ₹3,830,227.58 |
| West Bengal | ₹3,507,880.44 |
| Andhra Pradesh | ₹3,219,831.72 |
| Haryana | ₹2,882,092.99 |

Revenue is heavily concentrated in India's major metro states. Maharashtra, Karnataka, and Telangana alone account for a disproportionate share of total revenue — reflecting stronger e-commerce adoption and higher disposable income in these tech and business hubs.

### Analysis 6 — B2B vs B2C Comparison
| Customer Type | Total Revenue | Orders | Avg Order Value |
|---|---|---|---|
| B2C | ₹78,001,457.51 | 120,337 | ₹648.19 |
| B2B | ₹591,220.79 | 843 | ₹701.33 |

B2B customers represent less than 1% of total revenue but have a **higher average order value of ₹701 vs ₹648**. This is a significant untapped opportunity — scaling B2B order volume while maintaining the higher order value could drive disproportionate revenue growth.

---

## 💡 Business Recommendations

1. **Diversify category portfolio** — With 77% of revenue from just 2 categories, the business is overexposed. Invest in growing Western Dress and Top categories to reduce concentration risk
2. **Investigate the April to June revenue decline** — Identify whether this is seasonal or structural and implement targeted promotions to sustain revenue through summer months
3. **Reduce cancellation rate** — At 8.88%, cancellations are costing the business significant revenue. Investigate root causes — stock availability, pricing, or delivery timeframes — and implement fixes
4. **Improve delivery confirmation tracking** — Only 23.73% of orders are confirmed delivered. Better tracking and customer communication would improve trust and reduce disputes
5. **Expand into underserved states** — States outside the top 10 represent untapped markets. Targeted regional marketing campaigns could unlock new revenue streams
6. **Scale B2B operations** — B2B customers spend more per order. A dedicated B2B sales strategy could significantly boost revenue without proportionally increasing order volume

---

## 📂 Project Structure

```
amazon-ecommerce-sales-analysis/
│
├── ecommerce_sales_analysis.ipynb          # Jupyter Notebook with full analysis
├── .gitignore                              # Excludes large dataset file
└── README.md                               # Project documentation
```

---

## 👤 Author

**Toluwanimi Awofisayo**
Mathematics Graduate | Data Analyst
📧 temijasopelincoln@gmail.com
🔗 linkedin.com/in/irewamiri-awofisayo-745b9930a
