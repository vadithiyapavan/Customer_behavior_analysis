Customer Shopping Behavior Analysis
📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover meaningful insights related to spending patterns, customer segments, product preferences, discount usage, and subscription behaviors to support data-driven business decision-making.
The project follows an end-to-end analytics workflow:


Data Cleaning & Feature Engineering (Python)


Business Analysis (SQL on PostgreSQL)


Visualization & Reporting (Power BI)


Strategic Recommendations



📂 Dataset Summary


Rows: 3,900


Columns: 18


Key Features Include:


Customer demographics: Age, Gender, Location, Subscription Status


Purchase details: Item Purchased, Category, Season, Size, Color


Shopping behavior: Discount Applied, Review Rating, Frequency of Purchases


Transaction data: Purchase Amount, Shipping Type




Missing Data:


37 null values in Review Rating (imputed using median rating per category)





🛠️ Exploratory Data Analysis (Python)
Key steps performed:
✔ Data Cleaning


Checked structure using info() and describe()


Imputed missing review_rating using median by product category


Standardized column names to snake_case


✔ Feature Engineering


Created age_group using age binning


Derived purchase_frequency_days


Removed redundancy between discount_applied and promo_code_used


✔ Database Integration


Connected Python to PostgreSQL


Loaded cleaned data into the database for deeper SQL-based analysis



📊 SQL Analysis (PostgreSQL)
SQL queries were used to answer key business questions, including:


Revenue by Gender – Male vs Female spending patterns


High-Spending Discount Users – Customers using discounts yet spending above average


Top 5 Products by Average Rating


Shipping Type Comparison – Standard vs Express purchase behavior


Subscribers vs Non-Subscribers – Revenue & average spend comparison


Products Most Dependent on Discounts


Customer Segmentation – New, Returning, Loyal customers


Top 3 Products per Category


Subscription Likelihood of Repeat Buyers (>5 purchases)


Revenue by Age Group



📈 Power BI Dashboard
An interactive Power BI dashboard was developed to visualize:


Revenue distribution


Category-wise performance


Customer demographics & segments


Subscription-related spending


Shipping type comparisons


Product ratings & discount trends


The dashboard provides dynamic filters and actionable insights for business stakeholders.

📌 Key Insights & Business Recommendations
📍 1. Boost Subscription Rate
Subscribers contribute higher average revenue—strengthen exclusive benefits and marketing.
📍 2. Implement Loyalty Programs
Repeat buyers show strong long-term value; reward them with tailored offers.
📍 3. Review Discount Strategy
Discount-dependent products can affect profitability—optimize promotion planning.
📍 4. Promote High-Rated Products
Top-rated items can be highlighted in marketing campaigns for better conversions.
📍 5. Target High-Revenue Age Groups & Fast Shipping Users
Focus marketing and product placement on demographics with stronger purchase power.

🧰 Tech Stack


Python — Data cleaning & feature engineering


PostgreSQL — Business analysis using SQL


Power BI — Data visualization & dashboarding


Pandas, NumPy, Matplotlib, Seaborn — EDA


Jupyter Notebook — Workflow & documentation



📦 Project Structure
├── data/
├── notebooks/
├── sql/
├── powerbi-dashboard/
├── scripts/
└── README.md


👤 Author

Vadithiya Pavan Kumar Naik

Data Analyst | Python | SQL | Power BI | Dashboard Development

