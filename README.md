# PowerBI-US-Furniture-Sales

An end-to-end Power BI project with four interactive dashboards built on the US Furniture Sales dataset, covering sales performance, regional targets, sub-category insights, and monthly trends.

## Dashboard 1: Executive Dashboard
![Executive Dashboard](images/02-executive-dashboard.png.jpeg)

**KPIs:** Revenue 9.89M | Profit 286.40K | Discount 1.56K | Quantity Sold 38K | Products 17

**Key insights**
- Consumer is the largest segment (50.53% of revenue), followed by Corporate (31.06%) and Home Office (18.42%).
- West (3.14M) and East (2.92M) lead by region, while South is lowest (1.74M).
- Chairs and Phones are the top-selling sub-categories.
- Revenue grew steadily from about 2M in 2018 to about 3.1M in 2021.

## Dashboard 2: Detailed Sales Report
![Detailed Sales Report](images/03-detailed-sales-report.png)

- Table with profit trend indicators, quantity data bars, and a sales colour scale.
- Tables has the biggest loss (-17,725.48 profit) despite about 905K in sales.
- Copiers has the highest profit (55,617.82), and Phones and Accessories are also strong.
- Column chart of actual vs target by region, with DAX conditional colour coding (green = target met, red = below target).

## Dashboard 3: Monthly Sales Calendar
![Monthly Sales Calendar](images/01-monthly-sales-calendar.png)

- Calendar heatmap of daily revenue, with Year and Month slicers.
- Makes it easy to spot peak days and slow days.

## Dashboard 4: Branch Office – Employee & Sales
![Branch Office Employee and Sales](images/04-branch-office-employee-sales.png)

- Employee-level sales table (units sold, sales value) with Year and Month slicers.

## Process
1. **Data cleaning** in Power Query
2. **Data modeling**: relationships between fact and dimension tables
3. **DAX measures**: KPIs, conditional logic, colour coding
4. **Visual design**: slicers, navigation, calendar heatmap, storytelling

## Tools Used
Power BI, DAX, Power Query, Excel

## What I Learned
Building an end-to-end analytics workflow, from raw data to an interactive, decision-ready report.
