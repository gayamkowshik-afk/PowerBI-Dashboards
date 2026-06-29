# Power BI Dashboards Portfolio

A collection of 2 interactive Power BI dashboards covering social media ad performance and financial transaction analysis. Each is a single-page report built with DAX measures, slicers, and Power BI's native visuals.

| # | Dashboard | File | Domain |
|---|-----------|------|--------|
| 1 | [Meta Ad Performance Dashboard](#1-meta-ad-performance-dashboard) | `Facebook_and_Instagram_Analysis_Dashboard.pbix` | Social Media / Marketing Analytics |
| 2 | [Finance Analysis Dashboard](#2-finance-analysis-dashboard) | `Financial_Analysis_Dashboard.pbix` | Finance / Transaction Analytics |

---

## 1. Meta Ad Performance Dashboard

Tracks performance of Facebook & Instagram ad campaigns — reach, engagement, conversions, and budget — with breakdowns by audience demographics, geography, time, and ad format.

**KPI cards**
- Impressions: 216.0K
- Clicks: 25.4K
- Shares: 1.3K
- Comments: 2.6K
- Purchases: 1.3K
- Engagements: 29.3K
- CTR (Click-Through Rate): 11.76%
- Engagement Rate: 13.56%
- Conversion Rate: 5.21%
- Purchase Rate: 0.61%
- Total Budget: $2.5M
- Avg Budget / Campaign: $50.72K

**Visuals**
- **Comments by Target Gender** (donut) — Female 43% (1.1K), All 34% (0.9K), Male 22% (0.6K)
- **Comments by Users Age** (bar) — distribution of comments across age 18–50, peaking in the early 20s
- **Weekly Comments Trend** (stacked bar + line) — comment volume by week, broken out by category/segment
- **Comments by Country** (map) — geographic spread of engagement across North & South America, Europe, Africa, and Asia
- **Analysis by Month** (calendar heatmap) — daily intensity view for a selected month
- **Analysis by Ad Type** (table) — Impressions, Clicks, CTR, Purchase Rate, Engagement Rate, and Conversion Rate broken down by Video, Stories, Image, and Carousel ad formats

**Slicers:** Metric Fields, Campaign Name, Target Interests

**Key insight:** Female users drive the largest share of engagement (43%), and Stories/Video ad formats post the strongest CTR and conversion performance among the four ad types.

---

## 2. Finance Analysis Dashboard

Real-time view into financial transactions, customer segments, and risk indicators (FinSight) — built around transaction volume, fees, tax, and customer demographics for 2025.

**KPI cards**
- Total Amount: ₹137.53M (+1.41% vs previous year)
- Total Transactions: 15K (-0.57% vs previous year)
- Avg Transaction Value: ₹9.20K (+1.98% vs previous year)
- Total Fees: ₹216.94K (-0.17% vs previous year)
- Total Tax: ₹39.04K (-0.26% vs previous year)

**Visuals**
- **Total Amount by Month** (line/area) — Jan–Dec 2025 trend, peaking around June–July (~₹13M) with a dip in Feb (~₹10M)
- **Total Amount by Transaction Status** (donut) — Success 85.37% (₹117.41M), Failed 10.44% (₹14.35M), Pending 4.19% (₹5.76M)
- **Total Amount by Customer Segment** (bar) — Retail ₹76M, Premium ₹26M, SME ₹21M, Corporate ₹9M, Wealth ₹6M
- **Total Amount by State** (bar) — Maharashtra ₹22M leads, followed by Karnataka ₹16M, Gujarat ₹15M, Tamil Nadu ₹14M, Uttar Pradesh ₹13M, Madhya Pradesh ₹12M, Haryana ₹8M, Kerala ₹7M
- **Transaction Type Analysis** (table) — Amount, Fees, Tax, and Transaction count across Bill Payment, Card Payment, Deposit, Fee Charge, Interest Credit, Investment, Loan EMI, Refund, Transfer, and Withdrawal
- **Total Amount by Gender** (donut) — Female 52.77% (₹72.57M), Male 47.23% (₹64.95M)

**Pages:** Overview Analysis, Transactions

**Slicers:** Year, Dynamic Metrics, Occupation, Merchant Category

**Key insight:** Retail is by far the dominant customer segment by transaction value, 85%+ of transactions complete successfully, and Loan EMI / Card Payment are the highest-value transaction types.

---

## Tools used
- Power BI Desktop
- DAX (measures for rates, YoY comparisons, and dynamic metric switching)
- Power Query (data shaping/transformation)
- Slicers & bookmarks for interactivity

## Repository structure
```
├── Facebook_and_Instagram_Analysis_Dashboard.pbix
├── Financial_Analysis_Dashboard.pbix
└── README.md
```

## How to use
1. Download/clone the repo.
2. Open the `.pbix` file in Power BI Desktop (free download from Microsoft).
3. Use the slicers on each report page to filter by campaign, audience, year, segment, etc.
4. Hover over any visual for tooltips with exact values.
5. 
