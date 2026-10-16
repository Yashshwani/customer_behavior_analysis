Overview
This project presents a comprehensive end-to-end data analytics workflow designed to uncover actionable insights into customer purchasing patterns, product preferences, and sales trends. The pipeline spans from raw data ingestion and cleaning in Python, through relational database management and advanced querying in PostgreSQL, to executive-ready visualization in Power BI and presentation design via Gamma.

📊 Dataset
Source: Customer Shopping Behavior Dataset (Retail / E-commerce transactions).
Key Attributes: Customer ID, age, gender, item purchased, category, purchase amount (USD), location, size, color, season, review rating, subscription status, shipping type, and frequency of purchases.

🛠️ Tools & Technologies
Programming Language: Python (Pandas, NumPy, Matplotlib, Seaborn) for EDA and data cleaning.
Database & Querying: PostgreSQL (pgAdmin) for data warehousing and SQL analysis.
Visualization & BI: Power BI for interactive dashboard creation.
Documentation & Presentation: Markdown (Reports) & Gamma (Slide Deck).

⚙️ Project Workflow & Steps


Data Ingestion & Exploration (Python):
Loaded the raw dataset into a Jupyter Notebook using Pandas.
Conducted Exploratory Data Analysis (EDA) to inspect data types, identify missing values, and check summary statistics.
Data Cleaning & Preprocessing:
Handled missing values, standardized column names, and removed duplicates.
Exported the cleaned dataset for relational database import.
Database Management & SQL Analysis (PostgreSQL):
Created a structured PostgreSQL database table matching the schema.
Executed complex SQL queries (aggregations, window functions, CTEs) to answer specific business questions regarding customer lifetime value, top categories, and seasonal trends.

Dashboard Development (Power BI):
Connected Power BI to the processed dataset / PostgreSQL database.
Established table relationships, created custom DAX measures, and built an interactive dashboard.

Reporting & Presentation (Gamma):
Synthesized insights into a professional summary report.
Generated an executive slide deck using Gamma for non-technical stakeholders.

📈 Power BI Dashboard Highlights
Sales Overview: Total revenue, total transactions, and average order value (AOV).
Customer Demographics: Spending distribution across age groups, gender, and subscription tiers.
Product Performance: Top-selling product categories, seasonal demand fluctuations, and popular payment/shipping methods.
Interactivity: Dynamic slicers for filtering by season, location, and category.

💡 Key Results & Insights
Subscription Impact: Subscribed customers demonstrate a higher average order frequency, representing a key target segment for loyalty campaigns.
Category Dominance: Specific categories (e.g., Clothing and Accessories) drive the majority of total revenue, while seasonal spikes dictate inventory planning.
Customer Satisfaction: High review ratings strongly correlate with repeat purchases, emphasizing the importance of product quality.
