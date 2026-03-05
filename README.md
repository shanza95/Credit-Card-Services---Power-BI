# Credit-Card-Services---Power-BI 

## Project Overview
This project focuses on building an interactive Credit Card Customer Insights Dashboard using Power BI. The dashboard provides a comprehensive view of customer behavior, credit utilization, transaction activity, financial outcomes, and risk indicators. By integrating key credit card metrics, the dashboard helps business teams, analysts, and decision-makers understand patterns that drive profitability, customer satisfaction, and risk exposure.


## DASHBOARD 
<img width="2000" height="1156" alt="image" src="https://github.com/user-attachments/assets/1bf70dee-ffc2-4b0b-809e-9adefc86e4e7" />


## Key Areas of Analysis
- Revenue and Transaction Trends: the dashboard shows how revenue and transaction counts change across different quarters. This helps identify periods where spending activity is higher or lower.
- Spending Categories (Bills, Entertainment, Fuel, Grocery, Food, Travel)
- Customer Demographics (Education Level, Job Type)
- Card Category Performance (Blue, Silver, Gold, Platinum).

## Key Findings

The dashboard highlights important business metrics such as:
- Total Revenue (55.3M)
- Total Transaction Amount (44.5M)
- Interest Earned (7.8M)
- Total Transaction Count (655K)

**1. Blue Card Category Generates the Highest Revenue**

The Blue card category contributes the largest share of revenue compared to Silver, Gold, and Platinum cards.
This suggests that the majority of customers are using the basic credit card tier more frequently than premium cards.

**2. Swipe Transactions Are the Most Common**

Most transactions are completed using swipe payments, followed by chip payments, while online transactions are significantly lower.
This indicates that customers still prefer traditional in-store card usage over digital transactions.

**3. Bills and Entertainment Are Major Spending Categories**

Among the spending categories, Bills, Entertainment, and Fuel generate a large portion of the total revenue.
This suggests that customers commonly use credit cards for regular payments and lifestyle spending.

**4. Graduate Customers Contribute the Most Revenue**

Customers with a graduate education level generate the highest revenue compared to other education groups.
This may indicate that this group has higher purchasing power or more frequent credit card usage.

**5. Business and White-Collar Customers Generate Higher Spending**

Revenue is higher among business professionals and white-collar workers compared to other job categories.
This suggests that working professionals may rely more on credit cards for transactions.

**6. Transaction Activity Is Consistent Across Quarters**

The quarterly analysis shows that transaction counts and revenue remain relatively stable across quarters, with only small variations.
This indicates steady credit card usage throughout the year.

## Tools Used:
- Microsoft Power BI Desktop for report development and publishing
- Power Query for data cleaning and transformation
- DAX for calculated measures
- SQL & Python for data connection
- Excel dataset as the data source

## Workflow: CSV --> MySQL --> Power BI
*(Why not upload CSVs directly to Power BI)*

1. CSV files are imported into MySQL via Python
   - Python handles data transformation and automation.
   - MySQL acts as a central, scalable repository for multiple CSVs and large datasets.
3. Power BI connects to MySQL for reporting
   - Dashboards are built on clean, consistent data.
   - No need to manually refresh CSvs or worry about duplicates.

