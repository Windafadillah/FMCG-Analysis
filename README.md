# FMCG-Analysis

## Overview

#### This project analyzes transactional sales data from an e-commerce company to uncover insights related to product performance, promotional effectiveness, stock availability, and sales trends. The analysis is designed to support stakeholders such as sales, marketing, supply chain, and regional managers in making data-driven decisions.


## Business Questions
This project explores the following key questions:
1. Top-performing products: Which product categories or brands drive the most revenue and unit sales?
2. Promotional impact: How do promotions affect sales across different SKUs?
3. Stock vs. sales: Are stock issues or delivery delays affecting sales performance?
4. Channel efficiency: Which sales channels are most effective for specific product segments or regions?
5. Underperformers: Which products perform poorly despite being well-stocked or frequently promoted?

## Executive Summary
### Overview of Findings
1. Strong Start, Declining Momentum: The business experienced strong revenue growth in the first half of the year (January to June), as seen in the green bars of the YTD vs PYTD waterfall chart. However, performance declined steadily in the second half, with consistent revenue drops from July to November, signaling a need to investigate seasonal demand or operational constraints.

2. Channel and Product Contribution: Yogurt was the top-performing product, contributing the highest revenue (3M), followed by Milk and SnackBar. Retail remains the dominant channel, but E-commerce and Discount channels also contributed notably, suggesting multi-channel engagement is working.


3. Opportunities in Promotions and Stock: Promo sales contributed 25.3% of total revenue, and stock availability stood high at 97.9%, indicating strong operational efficiency. Yet, the business could benefit from revisiting promotion strategies during declining months to maintain momentum and drive unit sales.

![image alt](https://github.com/Windafadillah/FMCG-Analysis/blob/0404955f4292b8c6412071f2ea1a12e7af143d13/Executive%20Summary.png)

## Insights Deep Dive
### 1. Top Performing Products

- Yogurt dominates the FMCG portfolio, contributing over 40% of total revenue, indicating strong consumer preference or effective positioning.
- Milk and SnackBar are evenly matched, suggesting balanced market performance and possibly interchangeable consumer choice behavior.
- Juice has the lowest revenue contribution, despite being part of the core category. This could indicate:
      Poor distribution or availability
      Low demand
      Weak promotional support.


<img width="1367" height="692" alt="image" src="https://github.com/user-attachments/assets/0057b59b-0ea1-478f-9828-877db25b2d4b" />

Recommendation: 
- Focus product innovation and marketing efforts on Juice or consider repackaging or repositioning if strategic fit is confirmed.

### 2. Promotional Impacts
- Promotions drive volume but not always revenue: Across all years, promo-driven unit sales (blue line) generally peak during promotional months, but the corresponding revenue gains vary—highlighting possible discounting impacts.
- 2023 was the most promotion-heavy year: Promo sales peaked mid-year (especially June–July), aligning with the highest revenue months—indicating effective promotional execution.
- In 2024, promotions stabilized: While promo unit sales were steady, revenue increased gradually, suggesting improved pricing strategies or less discount-driven dependency.

Promotional impact on 2022
<img width="855" height="230" alt="image" src="https://github.com/user-attachments/assets/3276d55e-1c3a-4521-8c85-68aa3ef24eb2" />

Promotional impact on 2023
<img width="857" height="252" alt="image" src="https://github.com/user-attachments/assets/ea300f95-ca84-4765-a8a7-6716e42afea3" />

Promotional impact on 2022
<img width="872" height="257" alt="image" src="https://github.com/user-attachments/assets/418a618f-7dc3-4a9b-8589-ecccefec810a" />

#### Key Takeaways
- Promotions were most impactful in 2023, driving short-term spikes in both revenue and volume.
- 2024 shows strategic maturity—more revenue with stable promo activity suggests better brand pull or pricing optimization.
- The lack of sustained growth after promo peaks in 2022 and 2023 points to the importance of post-promo retention strategies.


### Stock vs. sales

<img width="812" height="275" alt="image" src="https://github.com/user-attachments/assets/2bb71c9c-0e5b-415d-97a4-56d9bb6abca4" />

The image above indicates that:
1. Correlated Trends: In general, Units Sold follow Stock Availability. When stock increases, sales also increase, and vice versa — indicating effective stock management in most periods.
2. Sales Drop with High Stock (Underperformance); Several time points show flat or decreasing sales despite high stock availability, indicating:
   - Poor product demand
   - Ineffective promotions
   - Visibility issues
→ These are potential underperformers worth investigating.
3. Stock-Out Impact; Periods where stock dips sharply and sales also drop point to stock-out issues, which suggest:
   - Missed sales opportunities
   - Forecasting or replenishment problems
4. Lag Effect: A few spikes in stock are followed by a delayed increase in sales, suggesting either:
   - Late campaign response
   - Promotion not aligned with stock arrival

### Channel Efficiency
<img width="1725" height="690" alt="image" src="https://github.com/user-attachments/assets/0cae2f79-d9ed-408b-8182-81e167b22c5b" />

Efficiency Signals
1. The retail channel carries most of the revenue load but shows declining contributions post-July, suggesting saturation or a lack of promotional push.
2. E-commerce performs best in Q2–Q3 — possibly due to campaigns, better availability, or higher consumer demand online during that period.
3. The discount channel shows little variation, low volatility, and low potential conversion, likely needing evaluation for future focus.


Key Takeaways
- 📉 Q4 Decline: All channels show a drop-off after July. This may be due to reduced promotions, seasonality, or supply constraints.
- 📈 Channel Balance: Heavy reliance on Retail; diversification via stronger E-commerce and Discount channel strategies may help balance risks.
- 🎯 Promo Targeting: Since E-commerce shows responsiveness, prioritize digital promotions and optimize Retail visibility to sustain growth.

### Underperformers
The Channel Efficiency quadrant analysis provides strategic insights into the relationship between product availability and sales performance across categories:

- Yogurt is positioned in the top-right quadrant (high sales, high availability), making it a star performer. This indicates excellent alignment between supply and demand, suggesting that current inventory and distribution strategies are working well.
- Milk, ReadyMeal, SnackBar, and Juice fall into the bottom-right quadrant (low sales, high availability), indicating overstocking. These categories may suffer from weak demand, insufficient visibility, or ineffective promotions. Marketing or bundling strategies could help boost movement.

This quadrant framework helps prioritize operational and marketing decisions to enhance channel performance and inventory efficiency.

<img width="620" height="292" alt="image" src="https://github.com/user-attachments/assets/3dff2d69-f0cc-4e02-8e66-8587e51afaa9" />

## Recommendation
1. Improve Stock Replenishment for High-Demand Products
   - Yogurt, a high-performing category, suffers from stock shortages. To prevent lost sales and meet demand:
     - Strengthen inventory forecasting models for top sellers.
     - Prioritize replenishment cycles for SKUs with recurring stockouts.
     - Consider safety stock levels or vendor lead time adjustments.
2. Reposition or Right-Size Low-Performing Categories
   - Juice and SnackBar have high stock levels but low sales, indicating overstocking or weak demand.
     - Reassess product-market fit or rebrand the category.
     - Explore aggressive promotions, bundling, or repositioning tactics.
     - Optimize inventory levels to reduce holding costs and avoid future overstock.
3. Support Retail and E-Commerce Channels Differently
   - Retail dominates in revenue but shows declining contribution post-July. E-commerce spikes mid-year and is more promo-responsive.
     - Retail: Improve in-store visibility and restock planning; align campaigns with seasonal peaks.
     - E-commerce: Continue targeted promotions and scale up digital presence during Q2–Q3.
4. Review Promotional Strategy Across SKUs
   - Promotions have a visible impact on sales volume, especially in 2023, but don't always translate into revenue.
     - Focus on promo ROI rather than frequency.
     - Plan campaigns aligned with peak shopping windows (Q2–Q3).
     - Pair promotional pushes with well-stocked inventory to avoid mismatches.
5. Address Operational Inefficiencies in At-Risk Categories
   - ReadyMeal shows both low sales and low availability, hinting at supply chain or listing issues.
   - Investigate upstream causes (supplier, distributor gaps).
   - Test consumer demand through limited relaunch or regional pilots.
   - Consider de-prioritizing or retiring if demand recovery is unlikely.
6. Monitor and React to Seasonal Declines
   - The consistent drop in performance from August to November across channels suggests seasonality or reduced campaign activity.
     - Build promotional calendars to re-engage customers in Q4.
     - Use past sales trends to drive demand planning and channel-specific targeting.
7. Implement an Underperformance Tracker
   - Create a dashboard module to continuously identify:
     - SKUs with high stock but low sales
     - Channels with declining conversion
     - Products that are over-reliant on promotions
       
This enables agile decision-making and resource reallocation to improve performance in real time.
