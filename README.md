# LITA-Project-Customer-Data

### Project Title: Customer Data Analysis

[Project Overview](#project-overview)
[Data Sources](#data-sources)
[Tools Used](#tools-used)
[Data Cleaning and Preparations](#data-cleaning-and-preparations)
[Exploratory Data Analysis](#exploratory-data-analysis)
[Data Analysis](#data-analysis)
[Data Visualization](#data-visualization)

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
   
[LITA Capstone Project (Pivot Table).xlsx](https://github.com/user-attachments/files/17637253/LITA.Capstone.Project.Pivot.Table.xlsx)

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
```

![Average Subscription Duration](https://github.com/user-attachments/assets/6964e37d-4094-4453-a6d5-cc8e0e56a0c8)
![Customer with subscriptions longer than 12 months](https://github.com/user-attachments/assets/c403b7de-7721-4548-a631-39ce054036c9)
![Customers who canceled their subscription within six months](https://github.com/user-attachments/assets/b4f3cb62-5a6b-427a-94fb-b015cdf877f4)
![The most popular suscription type by the number of Customers](https://github.com/user-attachments/assets/19b06497-4097-4646-b4f0-f030fc541bc4)
![Top 3 Regions by Subscription Cancellation](https://github.com/user-attachments/assets/68e99f23-034f-4f2a-ac97-3fcd01980a96)
![Total Number of Active and Canceled subscription](https://github.com/user-attachments/assets/98056b5c-bc19-4316-965a-d2a80bdbc13f)
![Total Number of Customers from each Region](https://github.com/user-attachments/assets/0ce86b2b-194c-4c4a-88b9-2e660a16653c)
![Total Revenue by subscription type](https://github.com/user-attachments/assets/979d5069-79f5-43c9-a967-427978f30b1a)

### Data Visualization

![POWER BI (CUSTOMER DATA)](https://github.com/user-attachments/assets/63a741dc-f0b9-4f67-9a62-9ac069d3a660)
