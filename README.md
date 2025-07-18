# A1 Motors Car Sales Analysis Project

This is a complete data analysis project on car sales and services performed for a fictional company A1 Motors. The project involves end-to-end data handling — from raw CSVs to dashboards — using tools like Excel, SQL Server (SSMS), Power BI, and Python. It also features ETL automation using Python and Task Scheduler.

## Project Objective

To analyze and understand the car sales, ownership patterns, insurance records, and service histories of A1 Motors and provide key business insights to help improve sales, customer retention, and operational efficiency.

## Role

As a Data Analyst, I was responsible for:
- Understanding business requirements
- Cleaning and transforming data
- Performing SQL-based analysis
- Visualizing insights using Power BI
- Automating the data pipeline using Python


## Project Workflow

### Step-by-Step Process:
1. Problem Understanding* 
   Understood the business problem and reviewed 5 raw datasets in `.csv` format:  
   - Car Data  
   - Sales Data  
   - Owners Data  
   - Insurance Data  
   - Service History  

2. ETL Process Using SQL Server (SSMS) 
   Loaded all CSV files into SQL Server using ETL.  

3. Data Modeling
   Created a master table using SQL JOINs on relevant fields across tables.

4. Data Cleaning 
   - Removed duplicates  
   - Handled null values  
   - Transformed columns (e.g., rounding amounts)  
   - Verified data types

5. SQL Insights 
   Performed queries to discover:
   - Top-selling models
   - Age group of buyers
   - Cities with highest orders
   - Gender-based buying patterns

6. Power BI Dashboard  
   Created a comprehensive dashboard showing:
   - Total Sales & Orders
   - Sales by Age Group, Gender, Model
   - Top Performing Cities
   - Customer Insights

7. Automation Using Python  
   Wrote a Python script to automate data refresh and scheduled it using Windows Task Scheduler.


## Tools & Technologies Used

- Excel – Initial data exploration
- SQL Server Management Studio (SSMS) – ETL, joins, cleaning, insights
- Power BI – Visual dashboard
- Python – Data automation
- Task Scheduler – Scheduling Python ETL jobs

##  Findings & Insights

>  Insight 1: Most orders came from Tier 1 cities  
>  Evidence: Sales volume by city shows high orders in metros  
>  Recommendation: Focus marketing budgets in metro areas

>  Insight 2: Customers aged 30–40 bought more cars  
>  Evidence: Age-based sales distribution peaked at 30–40  
>  Recommendation: Target offers and financing for that age range

>  Insight 3: Sedans had the highest purchase rate  
>  Evidence: Model analysis showed Sedan dominance  
>  Recommendation: Expand sedan inventory

>  Insight 4: Male customers had higher purchasing rates  
>  Evidence: Gender-based filter in dashboard  
>  Recommendation: Launch campaigns to engage more female buyers

## Conclusion

This project gave detailed insights into how A1 Motors operates in terms of sales and customer behavior. The dashboard allows stakeholders to make data-driven decisions while the automation ensures regular, up-to-date reporting with minimal manual work.

## Future Scope

- Predictive sales modeling using machine learning
- Real-time data sync using APIs
- Customer feedback sentiment analysis
- Integration with CRM platforms for end-to-end insights
- Profitability and warranty claim analysis





