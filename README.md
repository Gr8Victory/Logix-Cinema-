# Cinema Ticket Price Optimization Analysis

## Project Overview

This project analyzes cinema ticket sales and customer demand to determine whether a **demand-based pricing strategy** can improve revenue compared to a fixed pricing strategy.

The analysis evaluates ticket demand, ticket prices, tickets sold, optimized revenue, fixed revenue, full-demand revenue, and revenue losses resulting from unmet demand and pricing decisions.

The goal is to identify the most effective pricing approach and provide actionable recommendations that can help the cinema improve revenue and optimize ticket pricing.

---

## Business Problem

The cinema owner wanted to determine whether implementing **demand-based ticket pricing** would increase profitability compared to a fixed pricing strategy.

### Key Business Questions

- Does demand-based pricing increase revenue?
- When should ticket prices be increased or reduced?
- What factors contribute to revenue loss?
- How does customer demand affect pricing and revenue?
- Which pricing strategy generates the highest revenue?

---

## Dataset Overview

The dataset contains cinema ticket sales and demand information across multiple dates.

### Key Variables

| Column | Description |
|---|---|
| Date | Date of cinema operation |
| Demand/Orders | Number of customers demanding tickets |
| Price per Ticket | Ticket price based on demand |
| Tickets Sold | Actual number of tickets sold |
| Optimized Revenue | Revenue generated using the demand-based pricing strategy |
| Fixed Revenue | Revenue generated using a fixed pricing strategy |
| Full Demand Revenue | Potential revenue if full demand was satisfied |
| Revenue Profit/Loss (Unmet Demands) | Revenue impact from unmet customer demand |
| Revenue Profit/Loss (No Price Optimization) | Difference between optimized and fixed pricing |

---

## Pricing Strategy

The cinema uses a **volume-based pricing strategy** rather than a traditional surge-pricing strategy.

| Demand | Demand Percentage | Ticket Price |
|---|---:|---:|
| 500 people or below | 0% – 50% | ₦4,500 |
| Above 500 people | Above 50% | ₦4,000 |

### Pricing Logic

When demand is **500 people or below**, the ticket price is set at **₦4,500**.

When demand exceeds **500 people**, the ticket price is reduced to **₦4,000**.

The idea is to reduce the ticket price during periods of higher demand to attract more customers and increase overall ticket volume.

---

## Key Performance Indicators

The analysis produced the following overall results:

| KPI | Result |
|---|---:|
| Total Fixed Revenue | ₦43,164,000 |
| Total Full Demand Revenue | ₦42,359,500 |
| Total Optimized Revenue | ₦40,662,000 |
| Revenue Shortfall After Optimization | ₦2,502,000 |
| Revenue Shortfall from Unmet Demand | ₦1,697,500 |
| Total Tickets Sold | 9,592 |
| Total Orders/Demand | 10,080 |

---

## Key Insights

### 1. Fixed Pricing Generated the Highest Revenue

The fixed pricing strategy generated **₦43.16 million**, compared with **₦40.66 million** from the optimized pricing strategy.

This means the current demand-based pricing model did not outperform the fixed pricing model.

---

### 2. April Recorded the Highest Demand

April generated the highest customer demand during the period analyzed.

This indicates that April represents a strong sales period and provides an opportunity for the cinema to optimize screening capacity and revenue.

---

### 3. July Recorded the Lowest Demand

July recorded the lowest customer demand.

This suggests that promotional campaigns, targeted marketing, or carefully designed pricing incentives could be considered during low-demand periods.

---

### 4. Revenue Was Lost Through Unmet Demand

The analysis identified revenue losses resulting from customers whose demand could not be fully satisfied.

This highlights the importance of aligning cinema capacity and screening availability with demand.

---

### 5. Pricing Optimization Did Not Always Improve Revenue

Although the optimized strategy reduced ticket prices when demand exceeded 500 customers, the reduction in ticket price did not generate enough additional revenue to outperform the fixed pricing strategy.

This suggests that the current pricing thresholds and discount levels require further refinement.

---

## Monthly Revenue Analysis

The project also analyzed revenue performance across the months of **February to July 2026**.

### Monthly Optimized Revenue

| Month | Optimized Revenue |
|---|---:|
| February | ₦5,787,500 |
| March | ₦5,449,000 |
| April | ₦10,504,000 |
| May | ₦5,936,000 |
| June | ₦6,815,000 |
| July | ₦6,170,500 |

April recorded the strongest optimized revenue performance during the analyzed period.

---

## Dashboard & Visualizations

The Excel analysis includes visualizations covering:

- Revenue comparison
- Monthly revenue trends
- Revenue shortfall
- Profit/Loss from unmet demand
- Profit/Loss from pricing decisions
- Key Performance Indicators
- Pricing strategy analysis

These visuals were used to transform the raw ticket sales data into actionable business insights.

---

## Tools & Skills Used

- **Microsoft Excel**
- Data Cleaning
- Data Analysis
- Pivot Tables
- Data Visualization
- KPI Development
- Revenue Analysis
- Pricing Strategy Analysis
- Business Intelligence
- Business Insights & Recommendations

---

## Recommendations

Based on the analysis, the following recommendations were proposed:

1. **Refine the demand-based pricing thresholds** before full implementation.
2. **Increase screening capacity during high-demand periods.**
3. **Monitor customer demand trends regularly.**
4. **Use predictive analytics to forecast cinema attendance.**
5. **Review ticket prices monthly based on customer behavior.**
6. **Consider promotional pricing during low-demand periods.**
7. **Use historical demand data to improve future pricing decisions.**

---

## Business Impact

The analysis provides the cinema with a data-driven framework for evaluating ticket pricing decisions.

Rather than simply increasing or decreasing ticket prices, management can use customer demand, ticket sales, capacity, and revenue performance to determine when pricing adjustments are likely to create value.

The project also demonstrates that **pricing optimization should be continuously tested and refined**, rather than assuming that a lower price during high demand will automatically generate higher revenue.

---

## Conclusion

The analysis found that the current demand-based pricing strategy **did not outperform the fixed pricing model in terms of total revenue**.

Fixed pricing generated approximately **₦43.16 million**, while the optimized pricing strategy generated approximately **₦40.66 million**.

This indicates that the current pricing thresholds or discount levels need to be refined before implementation.

Future improvements could include incorporating customer behavior, historical attendance patterns, capacity utilization, and predictive analytics to build a more effective cinema pricing model.

---

## Author

**Victor Jackson**

Data Analyst | Excel | Power BI | SQL | Data Visualization

---

## Project Files

- `Cinema Ticket Price Optimization.xlsx` — Excel analysis and calculations
- `README.md` — Project documentation
- `Cinema Ticket Price Optimization Presentation.pptx` — Project presentation

---

## ⭐ Project Objective

> **Turn cinema demand and ticket sales data into actionable pricing decisions that improve revenue and customer utilization.**
