# LITA-Project-Customer-Data

### Project Title: Customer Data Analysis

### Project Overview
---
This project involves analyzing customer data for a subscription service to identify
segments and trends. Also, to understand customer behavior, track subscription types, 
and identify key trends in cancellations and renewals.

### Data Sources
---
The primary source of data used here is Customer Data Set uploaded by the Incubator Hub team on our Canvas LMS.

### Tools Used
---
- Microsoft Excel [Download Here](https//www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. For Data visualization
     
- SQL- Structured Query Language
  1.  For Data Querying
  
- Power BI  
  1. For Analyzing Data
  2. For Visualizing Data to generate insights

- GitHub for Portfolio Building

### Data Cleaning and Preparations
---
In the initial Phase of the Data cleaning and preparations, I performed the following:
1. Data loading and Inspection
2. Handling Missing variables
3. Data Cleaning and formatting

### Exploratory Data Analysis
---
This involved the exploration of the data to answer some questions such as;
- What are the subscription segments and trends
- What are the key trends in cancellation and renewal
- What are the subscription patterns

### Data Analysis
---
Here, I included some basic lines of queries used during my analysis

```SQL
select SubscriptionType, count (CustomerID) as cust_subscription from [dbo].[Customer Data]
Group By SubscriptionType
Order by cust_subscription desc

select* from [dbo].[Customer Data]
Where DATEDIFF(month, subscriptionStart, subscriptionEnd) <=6





