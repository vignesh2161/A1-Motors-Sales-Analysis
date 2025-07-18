# A1 Motors Car Sales Analysis Project

This is a complete data analysis project on car sales and services performed for a fictional company A1 Motors. The project involves end-to-end data handling — from raw CSVs to dashboards — using tools like Excel, SQL Server (SSMS), Power BI, and Python. It also features ETL automation using Python and Task Scheduler.

## Project Objective

To analyze and understand the car sales, ownership patterns, insurance records, and service histories of A1 Motors and provide key business insights to help improve sales and operational efficiency.

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
   
5. SQL Insights 
   Performed queries to discover:
   - Top-selling models
   - Sales of all years
   - Total sales per month
   - Fuel_types

6. Power BI Dashboard  
   Created a comprehensive dashboard showing:
   - Total Sales 
   - Sales by  Model
   - Total cars
   - Total models
   
7. Automation Using Python  
   Wrote a Python script to automate data refresh and scheduled it using Windows Task Scheduler.


## Tools & Technologies Used

- Excel – Initial data exploration
- SQL Server Management Studio (SSMS) – ETL, joins, cleaning, insights
- Power BI – Visual dashboard
- Python – Data automation
- Task Scheduler – Scheduling Python ETL jobs

##  Findings & Insights

>  Insight 1: Most sales from the months  
>  Evidence: Monthly sales between 109k to 117k throughout the year, but in March there will be a dip or loss. 
>  Recommendation: Focus marketing, promotions, and discounts in March.

>  Insight 2: Top 5 models  
>  Evidence: ACity and XUV 500 both are sold in 133k units, followed closely by creta (132k), duster (129k) and swift (128k). 
>  Recommendation: Target offers, advertisements, and inventory around the top 5 models.

>  Insight 3: Total sales per year  
>  Evidence: 2022: 649.3K, 2023: 645.3K, 2024: only 1.78K units
>  Recommendation: Carefully analyze the 2024 data. 
      
>  Insight 4: Fuel types distribution
>  Evidence: Diesel (10.2K), Electric (10.1K), CNG (10K), Hybrid (9.9K), and Petrol (9.8K) vehicles have very similar sales figures.
>  Recommendation: Maintain all types of fuels and increase electric vehicle stocks.

## Conclusion

This project provided valuable insights into A1 Motors' car sales, customer demographics, and service patterns. By integrating and analyzing multiple datasets using SQL, Power BI, and Python automation, the project enabled data-driven decisions to improve sales performance and customer targeting. It also showcases a complete data pipeline from raw data to dashboard and automation.

## Future Scope

- Predictive sales modeling using machine learning
- Real-time data sync using APIs
- Customer feedback sentiment analysis
- Integration with CRM platforms for end-to-end insights
- Profitability and warranty claim analysis





