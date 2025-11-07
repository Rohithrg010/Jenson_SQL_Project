🛒 Jenson USA Retail Performance Optimization (SQL Project)
This project features a comprehensive SQL-driven analysis of the Jenson USA retail dataset, designed to transform raw transactional and customer data into actionable business insights for optimization.
All querying and analysis were performed in MySQL Workbench against a multi-table relational database schema.
🎯 Project Goal
Leverage advanced SQL techniques to derive measurable insights across four key retail domains:
Customer Behavior
Staff Performance
Inventory Management
Store Operations
### 🛠️ Tools & Technologies

| Element | Detail |
|--------|--------|
| **Primary Tool** | SQL (Executed in MySQL Workbench) |
| **Dataset Schema** | Analysis performed across 9 relational tables (customers, orders, products, staffs, etc.) |
| **Advanced Techniques** | Complex JOINs, Aggregations (SUM/AVG), Window Functions (ROW_NUMBER), Set Operators (NOT EXISTS) |

| Business Area          | Outcome (Insight)                                                                              | Actionable Recommendation                                                                     |
| ---------------------- | ---------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Store Operations       | Identified top-performing stores by total products sold (e.g., *Baldwin Bikes* – 4,779 units). | Allocate more inventory/resources to top stores; investigate bottlenecks at lower-performers. |
| Inventory Optimization | Identified top 3 most in-demand products & all zero-demand SKUs (e.g., Trek 820-2016, etc.).   | Use dynamic stocking models; discontinue or markdown non-moving SKUs.                         |
| Staff Performance      | Highlighted above-average performing staff based on total items sold.                          | Build bonus structure; rotate high performers into training/mentorship roles.                 |
| Pricing Strategy       | Calculated median product price ($7,499.00) to establish pricing reference point.              | Use median as core benchmark for pricing/discount strategy alignment.                         |
| Customer Segmentation  | Found customers who purchased across *every* category (high-engagement group).                 | Launch tailored loyalty program to maximize LTV and retention.                                |

📁 Files in this Repository
Jensen_SQL_Milestone Project.pdf — final project report (visualizations, schema diagram, recommendations)
SQL Queries.pdf — full extracted SQL scripts used for the analysis (including ranking, aggregation, set-operator queries)
Author: Rohith Gowda Ranganatha
LinkedIn: [Insert LinkedIn hyperlink here]
