Executive Summary – Retail Sales Analytics (Python Project)
1.  Business Overview

This analysis explores a sample retail dataset containing product sales, customer purchases, and transaction-level details for January.
The objective is to uncover sales trends, identify top-performing products and customer segments, and provide actionable insights that could support decision-making in marketing, inventory planning, and pricing.

The project was completed using Python (Pandas & Matplotlib) and follows an industry-standard folder structure with separate outputs for charts and summary tables.

2.  Key Findings (High-Level Insights)
  

  Revenue Insights

* Total revenue for January: (£615.28)

* Top revenue category: Furniture (£322.97)

* Top revenue product: Standing Desk (£199.99)

* Highest spending country: United Kingdom

  
  Time-Based Insights

* Highest revenue weekday: Wednesday (£289.98)

* Slowest days: Friday & Saturday (≈ £17–£20)

  
  Customer Insights

* Customer C007 made the highest number of purchases (5 orders).

* Most customers made 2–3 orders, suggesting moderate purchase frequency.

* Top 5 customers by revenue collectively account for a significant portion of sales.


3.  Detailed Insights

 Product Performance

* The Standing Desk alone accounts for ~32% of total revenue.

Other strong performers include:

* Office Chair – £89.99

* Ergonomic Mouse – £39.99

* Monitor Stand – £32.99

* Majority of lower-priced items (USB cable, notebook pack, etc.) generate consistent but smaller revenue contributions.

  Implication:

High-ticket furniture items drive the largest share of income, while accessories contribute volume but not revenue.


  Category-Level Trends

* Furniture dominates revenue due to higher-value products.

* Electronics deliver moderate revenue despite higher sales frequency, indicating mid-priced items.

* Stationery generates the least revenue, as expected from low-cost products.

Implication:

Focus on expanding the furniture category or introducing new high-value items.

  
  Time-Based Patterns

* Wednesday is the strongest sales day, with revenue nearly 3–5× higher than slower days.

* Weekends underperform.

  Implication:
Introduce weekend promotions or shift marketing efforts to improve off-peak performance.


  Customer Behaviour

* Customer C007 appears significantly more active than others (5+ purchases).

* Remaining customers maintain steady but lower frequency (2–3 purchases).

* The revenue distribution by customer shows a typical “long tail” — few customers contribute disproportionately more.

  Implication:
Loyalty programs, personalised offers, or cross-sell campaigns could be targeted at high-frequency customers.

4.  Recommendations
 Business Actions

* Promote high-value items (Standing Desk, Office Chair) to maximise revenue.

* Bundle accessories with electronics to increase average order value.

* Introduce targeted offers for frequent buyers such as C007.

* Run mid-week campaigns to capitalise on high-performing days.


  Inventory Strategy

* Ensure strong stock levels for top revenue items, especially furniture.

* Reduce overstocking of low-rotation stationery items.


  Marketing Strategy

* Weekend discounts or flash sales could balance weekday/weekend performance.

* Promote ergonomics-related items together (desk + chair + mouse).



5. Technical Summary 

This project demonstrates:

* Data cleaning and manipulation using Pandas.

* GroupBy aggregations for revenue, quantity, and frequency metrics.

* Custom Matplotlib charts with data labels and improved readability.

* Exporting reusable summary tables as CSV for reporting/dashboarding.

* Professional folder structure following analytics workflow standards.

* Ability to turn raw data into clear insights and actionable recommendations.