# Global Software Sales Analytics
*Data Visualization & Business Insights using Tableau*


## Tools & Skills Demonstrated

- **Tableau Desktop** (Data Visualization & Dashboard Design)
- **Business Intelligence Storytelling**
- **KPIs & Trend Analysis**
- **Consumer Segmentation & Pricing Analysis**


## I. Business Context

This project presents a multi-page analytics dashboard designed to evaluate the sales performance of a **Global Software E-commerce Business**. The dataset consists of subscription and one-time purchase transactions across analytics, design, AI, productivity, and collaboration product categories. The goal of this analysis is to identify revenue patterns, customer behavior trends, product performance, pricing dynamics, and the impact of marketing and sales strategies across regions and channels.

This case study was developed using Tableau, supported by cleaning, modeling, and transformation of the data fields provided within the DataDNA public dataset.
--

## II. Business Objectives

The analysis addresses core business questions:

- How are revenue and product sales trending over time?
- Which channels bring in the most sales?
- Which channels bring the most repeat (loyal) customers?
- What percent of monthly sales comes from loyal customers?
- Which products or plans sell the most?
- Which products are most popular with loyal customers?
- How long do customers wait before their second purchase?
- Which discount codes are used most, and do they increase repeat purchases?
- What is the average selling price (ASP) by country or currency?
- Where do refunds happen most (by product or channel)?
- Do annual plans bring higher revenue per customer than monthly plans?

---

## III. Dataset Summary

This dataset simulates an e-commerce environment and includes the following:

**Entity Relationship Diagram**
![Entity Relationship Diagram](./ER_diagram.png)

--

## IV. Dashboard Structure

This Tableau project contains four dashboard sections:

### A. Performance Overview Dashboard

Provides a consolidated, high-level view of the company’s commercial performance for the latest reporting period. It is designed to help stakeholders quickly assess revenue health, sales volume movement, customer acquisition, and channel efficiency.

*Dashboard Preview*
![Performance Overview Snippet](./dashboard_snippets/d1.Performance_Overview.png)

## Key Metrics

- Net Revenue
- Units Sold
- New Customers
- Total Transactions
- Revenue Trend (Year-over-Year View)
- Traffic Channel Performance
- Top Performing Product Categories
- Location Based Performance

## Insights 

- $1.20M, showing a decline from $1.66M in the previous month.
- 10.69K units, down from 15.24K units previously.
- 210 new signups, slightly below the prior month (211).
- 1.77K transactions, compared to 2.51K last month.
- The trend comparison between Current Year (CY) and Previous Year (PY) shows strong performance early in the year, followed by a noticeable drop beginning in September.
- Overall pattern indicates broad channel underperformance, with Marketplace requiring urgent attention.
- Although Developer Tools remains the highest revenue generator, all categories show declines—indicating a broad slowdown in product demand, not isolated to a specific segment.
  
## Recommendations

- Strengthen Revenue Recovery
- Reassess Marketplace and Partner Channels
- Focus on High-Performing Categories
- Improve Customer Acquisition Pipeline
- Conduct Country-Specific Analysis
- Investigate Transaction Declines
- While the company maintains strong absolute revenue levels, the month-over-month downturn highlights the need for strategic intervention in channel performance, product demand stimulation, and customer acquisition.

## B. Customer Insights Dashboard

The Customer Insights Dashboard provides a comprehensive view of customer activity, behavior, and distribution for the current period. Its purpose is to help the organization understand customer retention, engagement patterns, demographic composition, channel-level performance, and geographic concentration. By visualizing churn, loyalty trends, and refund rates, this dashboard supports strategic decisions in customer experience improvement, retention programs, and targeted marketing.

*Dashboard Preview*
![Customer Insights Snippet](./dashboard_snippets/d2.Customer_Insights.png)

### Key Metrics:

- Active Customers
- Churn Rate
- Customer Behavior
- Demographics: Age Group
- Customer Segment Distribution
- Channel-Level Customer Refund
- Customer Concentration by Country

### Insights:

- 3.99K active customers, reflecting a 0.2% increase from last year, majority of which are Loyal Customers (80.86%).
- Strongest customer base is within the 25–34 age group, though showing a slight 0.1% decline.
- The Chun Indicates relatively healthy retention, but opportunities remain to re-engage lapsing segments.
- United States has the highest number of customers (1,213) with a +0.2% increase. Declines observed in Germany and France, requiring market-specific assessment.
- Time to second purchase: 45 days on average.
- Consumer segment leads with 2,529 customers (+0.2%), showing continued dominance.
- Marketplace shows relatively higher refund behavior, indicating potential quality or expectation mismatch for customers acquired there.

### Recommendation:
- Strengthen Retention & Reduce Churn : Leverage the strong loyal customer base for referral-driven growth.
- Leverage Behavioral Insights : The 45-day gap to second purchase provides an opportunity for targeted follow-ups at the 30–40 day mark.
- Focus marketing investment in growing regions like Australia, Netherlands, and Brazil.
- Improve Product Listing Accuracy for lesser refunds rates especially on Marketplace, some customer are relying heavily on descriptions.


## C. Product Insights Dashboard

The Product Insights Dashboard provides a comprehensive view of product performance across sales volume, refund behavior, category contribution, customer retention drivers, and revenue generation. Its purpose is to help stakeholders identify high-performing products, understand growth patterns, monitor refund drivers, and evaluate channel effectiveness.

*Dashboard Preview*
![Product Insights Snippet](./dashboard_snippets/d3.Product_Insights.png)

### Key Metrics:

- Unit Sold
- Refunded Units
- Product Status (Lifecycle Health)
- Product Growth Leaders
- Refunds Root Causes
- Loyal Customers’ Favorite Products
- Units Sold by Channel
- Best Selling Categories
- Top Revenue Drivers

#### Insights:
- 154.42K units sold, representing a 14.5% increase from last year. Higher refund volume suggests growth in sales but also signals potential quality, experience, or support issues that require monitoring.
- Majority of products are in Scaling or Neutral phases, indicating a healthy pipeline with a limited number of declining offerings.
- THe majority of Refund Reasons are Accidental Purchase but the sharp increase in service dissatisfaction is the most pressing issue, with highest percentage change.
- Azure AI Studio Annual Standard (Retention Score 48.86, ▲59.8%) is the favorite product among Loyal Customers.
- The Website channel shows the highest sales growth, indicating strong digital conversion and effective funnel performance.
- Developer Tools remains the dominant category, showing strong expansion in the last year.
- AI and productivity tool subscriptions show strong revenue acceleration.

#### Recommendation:
- Address High Refund Growth : Strengthening billing workflows to mitigate billing errors and duplicate orders. Reducing service dissatisfaction through UX improvements, clearer onboarding, and faster technical support.\
- Double Down on High-Growth Channels (Website, Partner, Reseller) : Invest in website optimizations, targeted ads, and improved checkout experience to capitalize on strong conversions.
- Manage Declining and Mature Products Strategically : Refresh marketing and upgrade paths for mature products to avoid revenue stagnation.
- Leverage Product Category Momentum : Expand offerings in Developer Tools and Analytics categories as they show the strongest growth.
- Strengthen Predictive Monitoring : Implement automated alerts for sudden spikes in refund causes.


## D. Sales Performance Dashboard

A consolidated analysis of sales and pricing performance across channels, customer types, subscription plans, and geographic markets. The objective is to monitor revenue performance trends, evaluate customer value, assess pricing effectiveness, and identify opportunities for growth and optimization. The data includes year-over-year comparisons, revenue distribution, customer loyalty metrics, and channel-level contribution insights.

*Dashboard Preview*
![Sales and Pricing Snippet](./dashboard_snippets/d4.Sale_Performance.png)

### Key Metrics:

- Yearly sales trends
- Channel contribution (Website, Partner Sales, Direct Sales)
- Revenue by geography (mapped visualization)
- Purchase patterns by currency and billing cycle

#### Insights:
- Net revenue increased significantly (+18.5% YoY), driven primarily by annual subscription buyers and repeat business, indicating customer retention and recurring revenue stability.
- Over 85% of revenue comes from loyal customers.
- Website and direct sales are the highest-performing channels with double-digit YoY growth.
- Marketplace and reseller channels are growing but at slower rates, suggesting lower operational efficiency or weaker customer targeting.
- With a 33.56% dependency on promotional pricing, customers appear highly price-sensitive, which may affect margin sustainability.
- Revenue is concentrated in a few key markets — primarily the United States, United Kingdom, and Canada, with emerging growth in Philippines and Spain.

### Strategic Recommendations:
- Strengthen Customer Acquisition Efforts: Invest in targeted marketing campaigns focusing on underpenetrated regions with emerging growth.
- Introduce satisfaction-based support programs and product education resources to prevent cancellations and returns.
- A/B test pricing models for monthly vs annual plans to reduce discount sensitivity.
- Improve partnership engagement and performance tracking for reseller and marketplace frameworks.
- Localize payment options and pricing for growing markets such as Australia, Philippines, and Spain.


## Key Findings Summary

| Category | Summary |
|----------|---------|
| Customer Behavior | Growth is strong, but early lifecycle retention needs improvement. |
| Product Sales | Top performers are subscription-based analytics-related tools. |
| Pricing Impact | Heavy discounting boosts conversion but weakens margin sustainability. |
| Geographic Trends | Strong revenue concentration in digitally mature regions. |
| Channel Strategy | Website drives volume; direct sales drives enterprise value. |
| Refund Pattern | Most churn occurs within the first month and ties to usability and Incidental purchase. |



## Recommendations for the Business

✔ Strengthen onboarding and reduce first-month churn with personalized guidance  
✔ Shift pricing strategy to focus fewer discounts and more bundling innovation  
✔ Invest in direct enterprise channels to accelerate ARPU growth  
✔ Improve currency transparency and regional pricing alignment  
✔ Expand lifetime value initiatives such as loyalty upgrades or annual billing incentives  

## Recommendations and Future Analysis

- Introduce Predictive Modeling: Forecasting demand, revenue, refund probability, and price sensitivity using machine learning would allow data-driven decision-making at scale.
- Enhance Customer Segmentation: Additional demographic attributes (behavioral signals, spend tiers, product usage metrics) can refine customer clusters and support targeted marketing strategies.
- Analyze Seasonality Trends: Deeper time-series analysis could uncover seasonal peaks and downturns in sales volume, helping inform inventory, marketing calendars, and pricing adjustments.
- Pricing Optimization: Elasticity modeling can determine ideal discount thresholds, recurring revenue effects, and sensitivity across regions and product categories.


## Project Reflection

This project provided an end-to-end analytical journey that transformed raw transactional and profile data into meaningful insights. Working across multiple tables — customers, products, and sales events — required careful data modeling, cleaning, normalization, and relationship mapping to ensure accuracy and consistency. Through visual exploration in Tableau, key business questions around customer behavior, product performance, revenue patterns, and pricing dynamics were answered with clarity and measurable context.
Completing this project highlighted the importance of thoughtful data design, iterative analysis, and storytelling. The dashboards demonstrate how analytics can shift from simple reporting to actionable intelligence — supporting decisions around marketing, pricing, retention, and product strategy.

--
🔗 **View the Interactive Dashboard Here:**  
 [Global Software Retail Analytics on Tableau Public](https://public.tableau.com/app/profile/daren.dale.aldea/viz/SoftwareRetailAnalytics/d1_PerformanceOverview)

# ⭐ If you found this helpful, consider starring the repository!
> Project Published: December 06, 2025
