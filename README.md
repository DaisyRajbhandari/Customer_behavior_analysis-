📊 Customer Behavior Analysis — Data Analytics Project

🔍 Overview

This project delivers an end-to-end data analytics workflow using a real-world customer shopping behavior dataset.
It covers the entire pipeline—from loading data in Python, cleaning and exploring it, storing it in PostgreSQL, querying it with SQL, and visualizing insights through a Power BI dashboard.

The goal is to demonstrate practical, job-ready skills in data analysis, SQL, database handling, and dashboard building.

📁 Dataset

File: customer_shopping_behavior.csv
Size: ~3,000 rows
Contains: demographic info, shopping categories, quantity, pricing, purchase dates, payment methods, etc.

The dataset is used to uncover:

Customer purchasing patterns

Popular product categories

Sales trends

Payment behavior

Total spending insights

🛠 Tools & Technologies

Python (Pandas, NumPy)

PostgreSQL (SQL queries, table creation, indexing)

SQLAlchemy (Python–Postgres connection)

Power BI Desktop (dashboard and visualizations)

pgAdmin (database GUI)

🧪 Steps in the Project
1. Load and Explore Data in Python

Imported dataset using Pandas

Displayed head, shape, column info

Performed EDA:

Missing value checks

Distribution analysis

Outlier detection

Category frequency analysis

2. Data Cleaning

Handled missing values

Converted data types (dates, numeric fields)

Cleaned categorical inconsistencies

Engineered new fields (e.g., total spend)

3. Load Cleaned Data into PostgreSQL

Connected using SQLAlchemy

Created a table named customer in Postgres

Loaded the cleaned DataFrame using .to_sql()

Verified table using SQL queries in pgAdmin

4. SQL Analysis

Performed SQL queries to answer:

Top-selling categories

Spending by gender

Highest revenue customers

Monthly sales trends

Payment method usage

5. Build Power BI Dashboard

The dashboard includes:

Revenue breakdown

Category sales

Customer demographics

Slicers for interactive filtering

The dashboard tells a clear story of what customers buy, how often, how much they spend, and how behavior changes over time.

📈 Key Results

Identified top revenue-driving categories

Found customer persona trends (gender, age groups)

Mapped seasonal spikes based on purchase dates

Showed which payment methods customers prefer

Built a clean, interactive dashboard for decision-making

🚀 How to Run This Project
1. Clone the repository
git clone https://github.com/DaisyRajbhandari/Customer_behavior_analysis.git
cd Customer_behavior_analysis

2. Install Python dependencies

3. Run the notebook

4. Set up PostgreSQL table

Update connection details in the script and run:

df.to_sql("customer", engine, if_exists="replace", index=False)

5. Open Power BI Dashboard

Open the file:

customer behavior dashboard.pbix
