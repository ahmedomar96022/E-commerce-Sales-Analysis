# UK E-Commerce Sales Analysis

## 1. Project Objective
This project analyzes transactional data from a real UK-based online retail 
store to identify who is actually driving revenue for the business, and how 
exposed that business is if its most valuable customers were to leave. The 
goal was to quantify customer concentration risk and turn that into a 
concrete, actionable recommendation.

## 2. Dataset Used
- **Source:** UCI Online Retail Dataset (publicly available on Kaggle)
- **Size:** 541,000+ transactions
- **Time period:** December 2010 – December 2011
- **Scope:** A UK-based online retailer selling to 38 markets

## 3. Questions (KPIs)
- Which customers contribute the most revenue, and how concentrated is that contribution?
- How did revenue trend month-over-month across the year?
- Which markets generate the most revenue, and which are most efficient per customer?
- How dependent is the business on its single highest-spending customer?
- What is the financial risk if top customers churn?

## 4. Process
- **Excel** — initial data cleaning and inspection
- **PostgreSQL** — deeper data cleaning, transformation, and analysis to answer the KPIs above
- **HTML, CSS, Chart.js** — built an interactive dashboard to visualize the findings

## 5. Dashboard
An interactive dashboard (`https://uk-e-commerce-dashboard.netlify.app/`) was built to visualize revenue trends, customer concentration, and market performance. Download the file and open it in any browser to explore it.

| File | What it is |
|------|------------|
| `https://uk-e-commerce-dashboard.netlify.app/` | Interactive dashboard — download and open in any browser |

## 6. Project Insight
- The top 10% of customers (just 434 people) were responsible for **61.4%** of all revenue. The bottom 50% generated less than 9% combined.
- Revenue grew steadily across the year, peaking in November 2011 at **£1.16M** — more than double the weakest month (February, £447K).
- The UK accounted for **82%** of total revenue across 38 active markets. The Netherlands, despite having only 9 customers, generated **£285K** — the highest revenue per customer of any international market.
- A single customer generated **£280K** on their own — a dangerous concentration of dependency for any business.

## 7. Final Conclusion
The business currently has no retention strategy, no VIP program, and no early warning system for high-value customer churn. Given that the top 434 customers drive the majority of revenue, this is a significant exposure. I recommend building a VIP retention program targeting these customers as a priority — losing even 50 of them could cost over £500K in annual revenue, with no current system in place to detect or prevent it.

## 8. Description
This project was built as part of my data analyst portfolio, simulating a real-world business problem: identifying revenue concentration risk and translating data into a strategic recommendation.

**Tools used:** Excel, PostgreSQL, HTML/CSS/Chart.js, Claude AI

---
*This project was built as part of my data analyst portfolio.*
