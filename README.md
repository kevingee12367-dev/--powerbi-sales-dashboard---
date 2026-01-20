E‑Commerce Sales Analysis — Power BI Project
📊 Project Overview
This project analyzes e‑commerce sales performance using Power BI. The goal is to demonstrate junior data analyst skills across data cleaning, modeling, visualization, and business insight generation.
The dashboard highlights key revenue drivers, customer behavior, product performance, and time‑based trends.
This project is part of my data analytics portfolio and showcases my ability to turn raw data into actionable insights.

 Tools & Technologies
- Power BI (data modeling, DAX, dashboard design)
- SQLite Database (ecommerce.db)
- CSV datasets (customers, products, transactions)
- Markdown for documentation
- GitHub for version control and project presentation

  
/powerbi/
    sales_dashboard.pbix

/data/
    customers.csv
    products.csv
    transactions.csv

/database/
    ecommerce.db

/insights/
    revenue_by_category_insights.md
    monthly_revenue_trend.md
    top_products_analysis.md

README.md

Data Sources
CSV Files (/data/)
These files were used for initial data exploration and Power BI import:
- customers.csv
- products.csv
- transactions.csv

SQLite Database (/database/ecommerce.db)
This database contains the same tables in a relational format and can be used to:
- Inspect the raw schema
- Run SQL queries
- Validate relationships
- Reproduce the data model outside Power BI
To access the database:
- Download ecommerce.db from the /database/ folder
- Open it using any SQLite viewer (DB Browser for SQLite, DBeaver, Azure Data Studio with SQLite extension, etc.)
- Explore the tables (customers, products, transactions)
- Run SQL queries to analyze or validate the dataset
This provides transparency into the underlying data and demonstrates SQL‑readiness for analytics workflows.

📈 Key Visuals in the Dashboard
1. Monthly Revenue Trend (Line Chart)
Shows how revenue changes over time using a Date Table and DAX measure.
2. Top Products by Revenue (Bar Chart)
Highlights the highest‑earning products.
3. Revenue by Product Category (Column Chart)
Provides a high‑level view of category performance.
4. KPI Cards
- Total Revenue
- Total Orders
- Average Order Value
- Number of Customers

🧠 Insights — Revenue by Category
Top Category: Books — $192,000
Second Category: Electronics — $181,000
Lowest Category: Home Decor — $151,000
Key Findings
- Books leads all categories with $192K in revenue.
- Electronics follows closely at $181K, only 6% lower.
- Home Decor underperforms significantly at $151K.
- Revenue is concentrated in the top categories, suggesting opportunities to improve product strategy for lower‑performing segments.

📌 Skills Demonstrated
- Data modeling (relationships, star schema)
- DAX measures (Total Revenue, calculated columns)
- Time intelligence (Date Table, YearMonth)
- Data cleaning and transformation
- Dashboard design and layout
- SQL database understanding (ecommerce.db)
- Business insight communication
- GitHub project organization

📥 How to Use This Project
1. Explore the Power BI Dashboard
- Navigate to /powerbi/
- Download sales_dashboard.pbix
- Open in Power BI Desktop
2. Review the Data
- CSV files are located in /data/
- SQLite database is located in /database/ecommerce.db
- You can open the database with any SQLite viewer to inspect tables or run SQL queries
3. Read the Insights
- Detailed analysis is available in the /insights/ folder
- Each .md file explains a specific visual or metric

📧 Contact
If you'd like to discuss this project or my work as a junior data analyst, feel free to reach out.






