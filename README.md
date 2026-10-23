# Customer Shopping Behavior Analysis
An end-to-end data analytics project exploring customer purchasing
patterns, subscription behaviour, discount usage, and product
performance using Python, PostgreSQL, and Power BI.

## Overview
Analyzed 3,900 purchase records to identify customer trends and
develop data-driven recommendations for subscription growth, customer
loyalty, and discount strategy.

## Tools & Technologies
- Python: Pandas, NumPy, Jupyter Notebook
- PostgreSQL & pgAdmin: Database management and SQL analysis
- Power BI: Interactive dashboard and data visualisation
- Gamma: Project presentation
  
## Project Workflow
1. Data loading and EDA: Inspected the dataset, data types, summary
   statistics, and missing values using Python.
2. Data cleaning: Imputed 37 missing review ratings using the
   median rating for each product category, standardised column names,
   and created features for age groups and purchase frequency.
3. SQL analysis: Loaded the cleaned data into PostgreSQL and
   answered 10 business questions about revenue, discounts,
   subscriptions, customer segments, product ratings, shipping, and age
   groups.
4. Dashboard development: Built a Power BI dashboard to monitor
   customer metrics, revenue patterns, subscription mix, and product
   performance.
5. Reporting: Prepared a written report and a Gamma presentation to
   communicate the findings and recommendations.
   
## Key Findings
- 3,900 purchase records across 25 products, 4 categories,
  and 50 locations.
- Average purchase amount: $59.76; average review rating:
  3.75.
- Subscribers represented 27% of the customer base.
- 839 customers used discounts while spending at least the average
  purchase amount.
- Hats had the highest reported product discount rate at 50%.
- Average purchase amount was $60.48 for Express shipping and
  $58.46 for Standard shipping.
  
## Dashboard
The Power BI dashboard summarises customer and purchase metrics,
subscription status, revenue by demographic groups, customer segments,
discount rates, and product ratings.

## Business Recommendations
- Test clearer subscription benefits to improve subscription
  conversion.
- Encourage repeat purchases through customer loyalty initiatives.
- Review discount strategies for products with high discount rates.
- Use product ratings and sales performance to guide product
  campaigns.
- Test targeted campaigns and measure results before scaling them.
  
## How to Run
1. Clone this repository:
   git clone <repository-url>
   cd customer-shopping-behavior-analysis
2. Install the Python dependencies used in the notebook:
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
3. Open Jupyter Notebook and run the analysis notebook:
   jupyter notebook
4. Create/configure your PostgreSQL database and run the SQL scripts in
   pgAdmin.
5. Open the .pbix file in Power BI Desktop and update the data source
   if needed.
Do not commit database passwords or other sensitive credentials. Update
file paths and database settings for your local environment.

## Deliverables
- Python notebook for EDA and data cleaning
- PostgreSQL SQL queries
- Power BI dashboard
- Analysis report and Gamma presentation
- 
Author: Minodya Nandasena
Skills: Python · EDA · Data Cleaning · PostgreSQL · SQL · Power BI · Business Reporting
