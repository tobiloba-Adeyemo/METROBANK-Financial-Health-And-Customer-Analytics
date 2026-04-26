# METROBANK-Financial-Health-And-Customer-Analytics

<img width="837" height="428" alt="image" src="https://github.com/user-attachments/assets/30b3abe0-d62a-40eb-a0e8-e31a530aed43" />

# Project Background 

MetroBank requires a consolidated analysis of customer accounts, deposits, loans, and credit performance to evaluate financial health and customer relationship strength. The primary goal is to understand account distribution, loan approval trends, and demographic balance in order to identify opportunities for growth and improved customer engagement.  

This project delivers a focused Excel dashboard that highlights deposit volumes, account types, loan performance by credit score, and customer segment balances, alongside demographic insights such as age group distribution.

---

## Key Insights and Analysis  

## Customer Demographics and Account Balances  

MetroBank serves 800 customers with a combined $212.3M in deposits. The average credit score across the portfolio is 580, reflecting moderate credit health. Multi‑account holders (237) highlight deeper engagement, showing that nearly one‑third of customers maintain multiple relationships with the bank.  

**Customer Segment Distribution:** Private customers hold $275.1K, Retail customers $267.1K, and Corporate customers $259.5K. Retail remains the growth driver, while Private and Corporate segments provide stable contributions, suggesting balanced engagement across all customer types.  

**Loan Performance:** Approved loans total $3.7M, but 50.4% of applications were rejected due to credit score thresholds. This highlights cautious risk management but also signals opportunities for financial literacy programs and tailored lending products to improve approval rates.  


**Account Type Distribution:** Savings accounts dominate the portfolio, followed by Checking, Credit Card, and Loan accounts. This reliance on savings indicates customer preference for secure deposit products, while credit products remain underutilized.  

**Loan Performance by Credit Score:** A slight majority of applications (50.4%) were rejected, showing that credit score thresholds are a significant barrier to loan approvals. This suggests a need for improved credit education or alternative lending strategies.  

**Customer Segment Breakdown:** Retail customers ($267.1K) represent the largest balance segment, followed closely by Private ($275.1K) and Corporate ($259.5K). Retail remains the growth driver, while Corporate and Private segments provide stable contributions.   

**Regional and Demographic Filters:** Interactive slicers allow stakeholders to analyze balances and loan performance by customer segment (Corporate, Private, Retail) and age group (Boomers, Gen X, Gen Z, Millennials), enabling targeted insights.  

---

## Technical Deliverables  

### Interactive Dashboard  
The Customer Insights Dashboard provides a clean, executive‑ready interface with KPI cards, bar charts, donut charts, and line graphs. It features interactive slicers for customer segments and age groups, allowing stakeholders to filter performance dynamically.  

### Time Intelligence Focus  
The project leverages advanced Excel functions and PivotTable calculations to derive comparative insights across account types, loan approvals, and demographic balances. Key technical features include:  

- **Dynamic KPI Cards:** Displaying deposits, accounts, multi‑account holders, loans, and credit scores.  
- **Comparative Bar Charts:** Benchmarking account types and customer segment balances.  
- **Donut Charts:** Visualizing loan approval vs. rejection by credit score.  
- **Line Charts:** Tracking age group balances to identify generational shifts.  
- **Zero‑External BI Reliance:** All logic and visualizations were built natively in Excel to demonstrate robust data modeling within a spreadsheet environment.  

---

## How to Use  

- **Slicers:** Use the sidebar filters to toggle between Corporate, Private, Retail, and generational groups.  
- **KPI Cards:** Monitor headline metrics such as deposits, accounts, loans, and credit scores.  
- **Charts:** Explore account type distribution, loan performance, and customer segment balances.  
- **Trend Lines:** Track age group balances to identify which demographics are driving growth.  

---

## Data Structure & Initial Checks  

### Data Overview  
The analysis was built entirely within a single Excel workbook, using a standard Excel Data Table as the source for all PivotTables and calculations. No data was loaded into the Power Pivot Data Model—all work was completed using native Excel functionality to demonstrate core spreadsheet competency and high‑performance dashboarding within a flat‑file environment.  

### Data Cleaning and Preparation  
The data cleaning and preparation process utilized native Excel tools, PivotTables, and standard Excel formulas to derive the core dashboard insights.  

**Data Quality:** Customer and account records were audited for duplicates and missing values before being converted into a structured Excel Table. This ensured that the $212.3M deposits and $3.7M loan approvals were grounded in accurate, verified records.  

**Field Engineering:** Helper columns were created using text and date functions to standardize account types, customer segments, and age groups. This allowed for seamless aggregation and comparison across demographics and product categories.  

**Aggregation:** PivotTables were used exclusively to aggregate deposits, balances, and loan approvals across multiple dimensions, such as account type, customer segment, and age group.  

**Time Intelligence (Calculated Measures):** Core KPIs—including deposits, accounts, loans, and credit score averages—were derived using calculated fields and formula‑based helper tables within the Excel workbook. This approach enabled dynamic comparisons and integrated trend lines without relying on the Power Pivot Data Model.  

---

## Technical Highlights  

**Dynamic Visuals:** Leveraged Excel’s charting tools and conditional formatting to create a clean, high‑contrast interface suitable for executive review.  

**Native Slicers:** Implemented interactive slicers for customer segments and age groups to provide filtered views of the dataset without manual table adjustments.  

**Formula‑Driven Logic:** Used GETPIVOTDATA and lookup functions to link KPI cards to back‑end Pivot summaries, ensuring the dashboard updates automatically as the source table grows.  
<img width="1350" height="674" alt="image" src="https://github.com/user-attachments/assets/9518d511-2313-49bf-9e8a-e7df04c82b9b" />

## Executive Summary (Customer & Account Performance)  
MetroBank is demonstrating stable deposit growth and balanced customer relationships, with Total Deposits reaching $212.3M across 800 accounts. Multi‑account holders (237) highlight strong customer engagement, while Approved Loans total $3.7M, supported by an average credit score of 580. This performance reflects cautious credit management alongside robust deposit inflows, ensuring financial stability.  

---

## Growth and Financial Efficiency  

**Strong Deposit Base:** Total Deposits stand at $212.3M, confirming MetroBank’s ability to attract and retain customer funds across savings and checking accounts.  

**Customer Engagement:** With 237 multi‑account holders, nearly one‑third of customers maintain multiple relationships, signaling trust and deeper engagement with the institution.  

**Loan Performance:** Approved Loans total $3.7M, but a slight majority of applications (50.4%) were rejected due to credit score thresholds. This indicates prudent risk management but also highlights potential barriers to loan growth.  

**Credit Score Insights:** The average credit score of 580 suggests a customer base with moderate credit health. This provides opportunities for financial literacy programs and tailored lending products to improve approval rates.  

**Segment Balance Distribution:** Retail ($267.1K) and Private ($275.1K) customers lead slightly over Corporate ($259.5K), showing balanced contributions across segments. Retail remains the growth driver, while Corporate and Private segments provide stability.  
<img width="637" height="69" alt="image" src="https://github.com/user-attachments/assets/d7d6a64c-4e40-43de-920a-e4a09f790a03" />

  ## Customer Segment Distribution  

**Core Segment Strengths:** Retail customers ($267.1K) and Private customers ($275.1K) are the standout contributors to overall balances. Their dominant position confirms that MetroBank’s strongest pull is in consumer and private banking services.  

**Secondary Segment:** Corporate customers ($259.5K) maintain a steady contribution. While stable, this segment represents a significant opportunity for growth if strategies used for retail engagement are applied here.  

**Underperforming Segment:** None of the segments are drastically lagging, but Corporate trails slightly behind Retail and Private. This suggests potential to strengthen corporate offerings, such as tailored lending or advisory services, to lift this segment further.  
<img width="189" height="151" alt="image" src="https://github.com/user-attachments/assets/39ebe010-5c81-4a1a-9da0-f1172a51f476" />
## Business Recommendations  

**Capitalize on Millennial Growth:** With Millennials holding the highest balances (~$290K), MetroBank should strengthen engagement with this demographic through digital banking innovations, tailored savings products, and lifestyle‑aligned financial services.  

**Expand Corporate Banking:** Corporate customers ($259.5K) provide steady contributions but remain underleveraged. Developing specialized credit facilities, treasury solutions, and advisory services can unlock further growth in this segment.  

**Revitalize Private Banking:** Private customers ($275.1K) represent a significant balance base but limited penetration in high‑net‑worth markets. Introducing premium services, wealth management offerings, and personalized relationship management could help grow this segment further.  

**Improve Loan Approval Rates:** With 50.4% of applications rejected due to credit score thresholds, MetroBank should explore credit education programs, flexible lending models, or alternative scoring mechanisms to expand loan accessibility without compromising risk management.  

**Strengthen Multi‑Account Relationships:** 237 multi‑account holders highlight deeper engagement. Expanding bundled account offerings, loyalty rewards, and cross‑product incentives can increase this number and deepen customer stickiness.  
  
---
Thank you for reading! Leave a comment if you have any questions about the analysis.
