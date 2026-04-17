Depiction of Sales Data — Power BI Dashboard
=============================================
 
A beginner Power BI project visualising sales performance data from the
Wide World Importers (WWI) dataset across products, employees, and time.
Built to practise data modelling, DAX measures, and interactive dashboard
design.
 
 
DASHBOARD PREVIEW
-----------------
Screenshot coming soon — open the .pbix file in Power BI Desktop to
explore the full interactive report.
 
 
WHAT'S INSIDE
-------------
The report contains a single interactive page with the following visuals:
 
  - Clustered Column Chart: Quantity of Items Sold by Calendar Year
  - Clustered Column Chart: Comparison of Total Quantity, Dry Items,
    and Chiller Items
  - Card Visual: Total Profit KPI at a glance
  - Table: Product-level breakdown — Description, Quantity, Revenue
    (incl. tax), Profit, and Employee
  - Slicer: Filter the entire report by Employee
 
 
DATA MODEL
----------
Dataset: Wide World Importers (WWI) — a Microsoft sample database
commonly used for data analytics and BI practice.
 
The report is built on a star-schema style model with the following tables:
 
  FactSale — transactional sales records including:
    Quantity, Total Dry Items, Total Chiller Items,
    Total Including Tax, Profit, Description (product)
 
  DimDate — date dimension providing Calendar Year for time-based analysis
 
  DimEmployee — employee dimension used for filtering and attribution
 
 
TOOLS & SKILLS USED
--------------------
  - Power BI Desktop (2026.03)
  - Data modelling with fact and dimension tables
  - DAX aggregations (SUM)
  - Interactive slicers and cross-filtering
  - KPI card visuals
  - Clustered column charts for trend and category comparison
 
 
HOW TO OPEN
-----------
1. Download and install Power BI Desktop (free) from powerbi.microsoft.com
2. Clone or download this repository
3. Open Depicton_of_Sales_Data.pbix in Power BI Desktop
4. Explore and interact with the dashboard!
 
 
AUTHOR
------
Akter Hosen
M.Sc. Applied Mathematics for Network and Data Sciences — HS Mittweida
 
LinkedIn : linkedin.com/in/akter-hosen-88b770195
GitHub   : github.com/Hosen-GIT
 
 
This is my first Power BI project — part of my learning journey in
data analytics and visualisation.
 
