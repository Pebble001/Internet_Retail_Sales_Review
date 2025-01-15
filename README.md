# Internet_Retail_Sales_Review

### Dashboard Link :  

## Problem Statement

This dashboard helps the business understand their sales pattern between the year 2009 and 2011. To provide insights to address business challenges relating to:
Customer segmentation
Customer retention
Sales trends across months, quarters and years
Product performance
Geographic insights


### Steps followed 

- Step 1 : Loaded data into azure data studio, dataset is an excel file.
  
- Step 2 : Opened a query page in azure data studio get some insights on the data through SQL queries
- Step 3:  Started with a union query to combine both tables together therby getting a whole look at the data across the years
- step 4:  Created a temporary table for the union table as #combinedtable
- Step 5:  Created the query for customer sementation finding recency, frequency and monetary value for all customers
  
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that none of the columns had errors & empty values.
  
- Step 5 : In the report view, under the view tab, theme was selected.
  
- Step 6 : Total sales, total customers, average frequency and average recency were calculated at 109.85M, 19,000, 6.35 and 5,80 respectively represented by card visuals.
  
- Step 7 : Percentage of customers without any purchase in the last 12 months was calculated at 3.52% 
- Step 8 : Line charts were introduced to illustrate Recency by customers and  monetary value by recency.

<img width="503" alt="Screenshot 2025-01-03 at 5 36 24 PM" src="https://github.com/user-attachments/assets/e51d73dd-9a24-4db0-bfc4-725c898a8276" />

- Step 9 : Column charts, donut and pie charts were also used to determine customer segmentations; decline or increase in 
monetary value frequency and recency 

<img width="1142" alt="Screenshot 2025-01-03 at 5 29 53 PM" src="https://github.com/user-attachments/assets/133cb374-2257-43da-9062-7aeffbcd9be3" />
