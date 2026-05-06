# MTN Q1 Market Performance & Churn Analysis 2026
![dashboard 1](/image/Revenue%20dashboard.png)
[ Click this text to interact with the full report and visualize the report](https://www.example.com)
## Project Overview hig

This project provides a comprehensive analysis of MTN’s Q1 performance, focusing on revenue drivers, subscription trends, device contributions, and customer churn dynamics. By segmenting customers into subscription tiers and analyzing geographic churn density, this dashboard identifies key areas for service improvement and revenue optimization.

## 🛠️ Skills & Competencies Demonstrated
### Technical Data Analysis:g
**Data Modeling & Transformation:** Organized raw datasets from Kaggle into structured tables suitable for complex analysis.  

**Advanced DAX (Data Analysis Expressions):** Developed custom measures to calculate KPIs such as Churn Rate, Total Revenue, and Subscriber Growth.  

**Conditional Logic & Segmentation:** Created a tiered subscriber system (Low, Middle, High) using SWITCH and IF logic to analyze customer spending behavior.  

**Geospatial Visualization:** Implemented map density visuals to identify regional churn "hotspots" and differentiate between relocation and competitor-driven exits.  

**Data Cleaning & Auditing:** Performed a deep dive into "Unknown" churn reasons, correctly identifying and re-classifying them as retained customers to ensure 100% data accuracy.

**KPI:** Evaluate the key customer retaintion indicators.

## Strategic Business Intelligence
**Churn Diagnostics:** Analyzed the "Why" behind customer loss, identifying that high call rates and competitor offers account for a significant portion of churn.

**Product Performance Evaluation:** Identified the revenue efficiency of hardware versus high-volume/low-margin data plans.

**Trend Forecasting:** Correlated the surge in February subscribers with a subsequent spike in churn rate to understand subscriber volatility.

**Revenue Optimization:** Analyzed profit margins across different months to identify which periods yield the highest sales and why.
## Data Storytelling & Design
**Professional Dashboarding:** Built 4 distinct dashboards (Revenue, Device/Plan, Churn, and Map) to provide a 360-degree view of business operations.

**Brand-Consistent UI/UX:** Applied MTN’s official brand identity (Yellow/Blue/Black) to create a cohesive and professional visual experience.  

**Executive Summary Reporting:** Translated complex technical findings into clear, actionable summaries for stakeholders.
## Tools Used
**Power BI:** Main visualization and modeling engine.  
**Power Query:** Used for initial data shaping and cleaning.
**GitHub:** Version control and portfolio hosting.

## Key Insights by Dashboard
1. **Revenue & Subscription Trends:** The first quarter saw a total revenue of ₦199 Million, with a significant peak in the middle of the quarter.

![dashboard 1](/image/Revenue%20dashboard.png)


- Monthly Performance: February was the powerhouse of Q1, contributing 46.2% of total revenue.
- Subscriber Volatility: There was a massive influx of users in February (450 subscribers) compared to January (271) and March (253).
- The Churn Correlation: Interestingly, as subscribers peaked in February, the churn rate spiked to 14.58% (up from 6.67% in January) before stabilizing at 7.91% in March.
- Customer Satisfaction: Despite churn fluctuations, the most frequent service rating remains a solid 4/5 stars.

2. **Device & Plan Revenue Contribution:** This section analyzes which hardware and data products drive the most value.

![alt text](/image/Device%20&%20Plan%20Revenue.png)
- Hardware Impact: 
5G Broadband: The primary revenue driver, contributing ₦100 Million.
4G Router: Contributed ₦37 Million.
Mobile SIM: Contributed ₦13.4 Million Naira.

- Plan Efficiency: High Volume: The 60GB Monthly plan is the most popular (81 subscribers) but generates moderate revenue (₦13.1M).
- High Value: The ₦1.5TB Yearly plan is the most efficient, generating the highest revenue despite having only 25 subscribers.
- Low Performance: Daily and short-term plans (500MB Daily, 1.5GB/2.5GB 2-Day) contribute the least to the bottom line, with the 500MB plan generating only ₦112,700. 

3. **Churn Diagnostic & Customer Segmentation:** To understand why customers leave, I performed a deep dive into churn reasons and categorized the user base into financial tiers.

![alt text](/image/churn%20analytics.png)
- Churn Distribution: Retention: 70% of the customer base remains active.
- Churned: 29.5% of customers have left the service.
- Primary Drivers: High call rates and better competitor offers account for approximately 10% of total customer loss.
- Customer Tiering: I segmented the customer base into three tiers based on monthly spend;
Low Subscriber ≤ ₦10,000
Middle Subscriber ≤ ₦30,000
High Subscriber > ₦30,000

4. **Geographic Churn Density (Map Analysis):** The map visualization identifies regional pain points across Nigeria.

![alt text](/image/map%20density.png)
- Relocation Hotspots (Green): States like Kaduna show high rates of churn specifically due to customers relocating.
- Competitor Risk (Dark Red): States highlighted in dark red indicate a high risk of churn driven specifically by better offers from competitors.
- General Churn (Red): Identifies general dissatisfaction or network-related exits.

## Conclusion
The analysis concludes that February’s peak in revenue and subscriber acquisition was undermined by a sharp spike in churn, highlighting a critical need for improved retention strategies. To optimize growth, the 60GB monthly plan—which currently leads in subscriber volume but generates moderate revenue—should be leveraged to convert low-tier customers or serve as a blueprint for new, entry-level plans. Finally, addressing regional dissatisfaction in "competitor risk" states and reducing losses due to high call rates are essential to lowering the overall 29.5% churn rate.
