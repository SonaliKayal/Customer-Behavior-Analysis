# Customer-Behavior-Analysis

🛍️ Customer Shopping Behavior Model


This project analyzes customer shopping behavior using transactional data to uncover insights about spending patterns, product preferences, and demographic trends.
The goal is to understand how customers interact with products and offers and to help businesses make data-driven decisions that enhance customer engagement and sales performance.

The workflow covers the entire data analytics pipeline — from data loading and cleaning in Python, SQL-based querying, and visualization in Power BI, to generating a final report and presentation in Gamma.

📌 Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (SQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

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
- Environment	: Jupyter Notebook / VS Code
  
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

Revenue & Sales by Category

Revenue by Age Group

% of Customers by Subscription Status

Revenue by Shipping Type

Filters for Gender, Category, Subscription Status, and Shipping Type

📊 Results & Insights:-

Clothing generates the highest revenue and sales volume.

Young Adults and Middle-aged customers are the top contributors to revenue.

Subscribers account for 27% of customers but generate higher per-order value.

Discount usage boosts sales but can impact profit margins.

Express shipping users tend to have higher purchase amounts.

💡 Business Recommendations:-

Boost Subscriptions: Offer exclusive benefits to increase the subscriber base.

Customer Loyalty Programs: Reward repeat buyers to strengthen retention.

Optimize Discounts: Apply smart discounting to balance revenue and margin.

Promote Top Categories: Highlight high-revenue categories in campaigns.

Targeted Marketing: Focus on high-value demographics and shipping preferences.

⚙️ How to Run

- Clone the Repository

git clone https://github.com/yourusername/customer-shopping-behavior-model.git
cd customer-shopping-behavior-model


- Install Required Libraries

pip install pandas numpy matplotlib seaborn pyodbc


- Run the Python Notebook

- Load the dataset and perform EDA.

- Export the cleaned data for SQL analysis.

- Run SQL Queries

- Import the cleaned CSV into SQL Server.

- Execute provided SQL scripts to extract insights.

- Visualize in Power BI

- Connect Power BI to SQL Server.

- Use the provided .pbix file to view and customize the dashboard.

- View the Report

Open the Gamma presentation for a concise storytelling summary of findings.
