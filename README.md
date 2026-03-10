# 🚗 Car Sales Dashboard – SwiftAuto Traders Analysis

## 📌 The Business Problem
SwiftAuto Traders, a regional chain of car dealerships, was struggling to 
answer a critical question: **which dealers and models are actually driving 
revenue — and which are falling behind?**

Without a centralized view of sales and service data, regional managers 
were making decisions based on gut feeling rather than data. Profits varied 
wildly across dealer locations, certain car models were underperforming, 
and service issues like recalls were going untracked — all of which posed 
a serious risk to the business.

**My role:** Step in as a Data Analyst, dig into the numbers, and build a 
dashboard that turns raw sales data into clear, actionable insights.

---

## 🔍 The Approach
I analyzed 1,200+ records of monthly car sales data spanning multiple 
dealers, models, and years. The analysis was conducted in two phases:

### Phase 1 – Exploratory Analysis in Excel
Before building any dashboard, I used Excel to explore the data and 
identify patterns:
- Which dealers were moving the most units?
- How did profits trend over time across different models?
- Was the Hudson model a consistent performer across all dealers?

### Phase 2 – Executive Dashboard in IBM Cognos Analytics
With the key questions defined, I built a two-page interactive dashboard 
for leadership to monitor performance in real time.

---

## 💡 Key Findings

| Insight | Detail |
|--------|--------|
|  Top Dealer | Dealer **1288** sold the most cars (2,644 units) and generated the highest profit |
|  Underperformer | The **Champlain** model had the lowest total profit at just $2.38M |
|  Recall Risk | Certain models showed disproportionately high recall rates in specific systems |
|  Customer Sentiment | The majority of customer reviews were **Positive**, but Negative sentiment warranted attention |
|  Profit Total | Combined dealer network generated **$78.4M** in total profit |

---

## 📊 Dashboard Overview

### Sales Page
Designed for the regional sales manager to track revenue KPIs at a glance:
- Total Profit: **$78.4M**
- Total Units Sold: **58,118**
- Average Units Sold per transaction: **19.3**
- Profit breakdown by Dealer ID (sorted ascending to spotlight 
low performers)
- Quantity sold comparison across all car models

### Service Page
Designed for the service operations team to proactively manage 
risk and customer experience:
- Recall volume by car model — to prioritize service resources
- Customer sentiment analysis — to flag experience issues early
- Monthly sales vs profit trends — to catch seasonal dips
- Recall heatmap by model and affected system — to identify 
systemic product issues

---

## 📁 Repository Contents
| File | Description |
|------|-------------|
| `CarSalesByModelEnd.xlsx` | Excel workbook with 4 analytical charts |
| `Car_Sales_Dashboard.pdf` | Full Cognos Analytics dashboard (Sales & Service) |

---

##  Tools & Skills Demonstrated
- **Microsoft Excel** – Pivot tables, chart creation, data aggregation
- **IBM Cognos Analytics** – Dashboard design, KPI cards, 
treemaps, heatmaps
- **Data Storytelling** – Translating raw data into business insights
- **Business Intelligence** – Building dashboards for executive audiences

---

##  Data Source
Dataset provided by IBM via the Coursera 
IBM Data Analyst Professional Certificate program, 
sourced from the IBM Accelerator Catalog.
