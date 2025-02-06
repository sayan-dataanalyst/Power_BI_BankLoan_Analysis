# Bank Loan Analysis Project - Banking Domain
## Problem Statement:
Our bank lends loans to the market on risk taking basis and in recent times they have noticed that some loans are recovering as per the planned timelines but in some cases, our bank is not receiving money from borrowers and eventually they are being charged off. Currently we do not have any data driven tool for the managers to do deep assessment.  

## Solution:
In order to monitor and assess our bank's lending activities and performance, we need to create a comprehensive Bank Loan BI Report for better insights. This report aims to provide insights into key loan-related metrics and their changes over time. The report will help us to make data-driven decisions, track our loan portfolio's health, and identify trends that can inform our lending strategies.

## Steps in project:
1. Data downloaded from kaggle.com
2. Data walkthrough
3. Data cleaning and quality check in power query editor
4. Data modelling 
5. DAX calculations
6. Dashboard lay outing
7. Charts development and formatting 
8. Report development 
9. Insights generation


## Model Page: 
Data ingested from csv flat file and created a star schema model.





![Model Page](https://github.com/user-attachments/assets/93bd45d9-3405-40e8-b9d3-53be66f7f116)





## Key Performance Indicators: 
	Total loan applications with Month-to-Date (MTD) applications received and Month-on-Month (MoM) loan application variances. 
	Total loan amount given (funded amount) with Month-to-Date (MTD) fund given and Month-on-Month (MoM) funded variances.
	Total loan amount received from borrowers with Month-to-Date (MTD) amount received and Month-on-Month (MoM) variances.
	Average interest rate with Month-to-Date (MTD) and Month-on-Month (MoM) analysis.
	Average debt-to-income (DTI) ratio with Month-to-Date (MTD) and Month-on-Month (MoM) analysis.


## Page 1 (Summary Page): 
A comprehensive analysis and evaluation of key aspects of loan details and their status, uncovering key insights based on state-wise and monthly trends in loan status, interest rates, and borrowers' loan purposes.






![BankLoanSummaryPage](https://github.com/user-attachments/assets/455eb237-c890-49cb-83cd-f83fa0190016)












## Page 2 (Bad Loan Analysis): 

Considering the problem statement, a dashboard was developed to analyse bad loans (charged-off) to mitigate losses, providing a comprehensive review from multiple. perspectives.

![Bad Loan Analysis Page](https://github.com/user-attachments/assets/249d6dad-7b18-4bc2-948f-31aa774e0e1c)

### Drill Through Page: 
The drill-through page was created for an in-depth analysis of bad loan events, drilling from bad loan application counts (from KPI). 
![Drill Through Page 1](https://github.com/user-attachments/assets/e591fb15-761f-4c94-9b5a-cb94798ee930)


## Page 3 (Good Loan Analysis): 

A similar dashboard was created to analyse good loan (fully paid and current loans), providing a comprehensive review from multiple perspectives.
![Good Loan Analysis Page](https://github.com/user-attachments/assets/0d61af2c-ae44-4624-a4ba-98807258c2cc)

### Drill Through Page: 
The drill-through page was created for an in-depth analysis of bad loan events, drilling from good loan application counts (from KPI). 

![Drill Through Page 2](https://github.com/user-attachments/assets/9cbacbca-22cb-410a-9722-6eeb539d8722)



