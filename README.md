# Customer-Behavior-Analysis

🛍️ Customer Shopping Behavior Model


This project analyzes customer shopping behavior using transactional data to uncover insights about spending patterns, product preferences, and demographic trends.
The goal is to understand how customers interact with products and offers and to help businesses make data-driven decisions that enhance customer engagement and sales performance.

The workflow covers the entire data analytics pipeline — from data loading and cleaning in Python, SQL-based querying, and visualization in Power BI, to generating a final report and presentation in Gamma.

📌 Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboards that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.

<img width="1275" height="689" alt="Pipeline Image" src="https://github.com/user-attachments/assets/571cb553-c22e-45df-823f-bae86b4b295c" />




🧾 Dataset

- Total Records: 3,900

- Columns: 18

- Key Attributes:

  - Customer demographics: Age, Gender, Location, Subscription Status

  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

   - Behavioral data: Discount Applied, Previous Purchases, Review Rating, Shipping Type

- Missing Data: 37 missing values in Review Rating, imputed with median values per category.

🛠️ Tools & Technologies

Category	Tools Used:-

- Programming & Data Prep	Python : (Pandas, NumPy, Matplotlib, Seaborn)
- Database Querying : 	Microsoft SQL Server
- Visualization :	Power BI
- Presentation	: Gamma (for storytelling and interactive slides)
- Environment	: Jupyter Notebook 
  
🔍 Steps & Process:-

1️⃣ Data Loading and Cleaning (Python):-

Imported dataset using Pandas.

Checked structure using info() and describe().

Imputed missing review ratings using median per product category.

Standardized column names to snake_case for consistency.

Created new features:

age_group (based on age bins)

purchase_frequency_days (from timestamp data)

Exported the cleaned dataset for SQL analysis.

2️⃣ Data Analysis (SQL Server):-

Executed analytical SQL queries to extract key insights:

Revenue by Gender – Compared total revenue by male vs. female customers.

Top Products by Rating – Found products with the highest average review rating.

Revenue by Shipping Type – Compared sales from Standard vs. Express delivery.

Subscribers vs. Non-Subscribers – Analyzed differences in average purchase and total revenue.

Discount Impact – Identified products heavily dependent on discounts.

Customer Segmentation – Classified users as New, Returning, or Loyal based on purchase history.

Revenue by Age Group – Evaluated which demographic drives the most revenue.

3️⃣ Dashboard (Power BI) :-

Created an interactive Power BI dashboard to visualize key insights.

Dashboard Highlights:-

KPIs: Total Customers, Avg Purchase Amount, Avg Review Rating

Visuals:-

- Revenue & Sales by Category

- Revenue by Age Group

- % of Customers by Subscription Status

- Revenue by Shipping Type

- Filters for Gender, Category, Subscription Status, and Shipping Type

Page 1 (Customer Overview Dashboard)

<img width="1317" height="720" alt="dashboard SS" src="https://github.com/user-attachments/assets/eda0be57-d10b-405a-9cd2-cf3c38f220de" />

Building on the foundational overview, Page 2 (Customer Trends And Performance) of the dashboard delves into the core drivers of customer value and operational effectiveness. This section provides a granular view of what makes customers loyal, how they spend, and when they are most active, enabling highly targeted business strategies.


This dashboard page provides deeper insights into customer loyalty patterns, purchasing habits, and seasonal trends that drive business performance.

Key Findings:

- Customer Loyalty: Strong repeat purchase behavior with average of 25 previous transactions per customer
- Subscription Impact: Subscribers generate 99% higher revenue despite being only 27% of customer base
- Purchase Frequency: 89-day average cycle indicates opportunity to increase purchase frequency
- Seasonal Trends: Spring and Winter are peak revenue seasons, guiding inventory planning
- Payment Preferences: Credit cards dominate with 17.29% of total payment volume
- Top Locations: Montana, Illinois, California are highest-performing states
- Category Performance: Accessories show highest repurchase rate, indicating strong customer retention
- Discount Effectiveness: Outerwear category responds best to discount strategies
- Revenue Drivers: Middle-aged and Adult segments contribute most to overall revenue

Page 2 (Customer Trends And Performance)

<img width="1253" height="708" alt="Screenshot 2025-11-18 223133" src="https://github.com/user-attachments/assets/2ad4932f-ff87-449d-978b-b4afdefffc89" />


📊 Results & Insights:-

- Clothing generates the highest revenue and sales volume.

- Young Adults and Middle-aged customers are the top contributors to revenue.

- Subscribers account for 27% of customers but generate higher per-order value.

- Discount usage boosts sales but can impact profit margins.

- Express shipping users tend to have higher purchase amounts.
  
- Strong loyalty: 25 average previous purchases per customer

- Subscribers deliver 99% higher lifetime value

- 89-day purchase cycle presents engagement opportunity

- Spring & Winter are peak revenue seasons

- Credit cards dominate payments (17.29% share)

- Montana, Illinois, California are top-performing states

💡 Business Recommendations:-

Based on Page 1 Insights:

Promote Top Categories: Increase marketing focus on Clothing and Accessories, which generate highest revenue and repurchase rates

Target High-Value Demographics: Create tailored campaigns for Young Adults and Middle-aged customers who drive 65% of revenue

Optimize Shipping Options: Promote Express shipping to leverage its 15% higher purchase amounts

Based on Page 2 Insights:

- Boost Subscription Conversions: Leverage the 99% revenue premium from subscribers with exclusive benefits and targeted onboarding

- Enhance Loyalty Programs: Capitalize on strong repeat behavior (25 avg purchases) with tiered rewards for frequent buyers

- Strategic Discount Management: Apply smart discounting on Outerwear (most responsive) while protecting margins on Clothing

- Seasonal Inventory Planning: Align stock levels with Spring and Winter revenue peaks

- Geographic Expansion: Concentrate marketing efforts on top-performing states (Montana, Illinois, California)

- Purchase Frequency Improvement: Develop campaigns to reduce the 89-day purchase cycle through personalized reminders

View the Report

Open the Gamma presentation for a concise storytelling summary of findings.
