# FINANCIAL-EXPENSE-Dashboard
📊 Financial Performance & Budget Variance Dashboard📌 
Project Overview:
This project presents an interactive Power BI Dashboard built to track, analyze, and visualize corporate expenditures against allocated budgets across departments, regions, cost categories, and payment channels.

🛠️ Tools & Technologies Used: 
1. Microsoft Excel: Raw data cleaning, preprocessing, and missing value handling. 
2. Power BI Desktop: Data modeling, DAX measure creation, visual interactive reporting, and dashboard layout. 
3. Power Query: Data transformation, automated schema cleanup, and column data type formatting.
4. DAX (Data Analysis Expressions): Custom key performance indicators (KPIs), dynamic variance calculations, and percentage metrics.

🔑 Key Highlights & Summary Statistics:
1. Dataset Scope: 10,010 cleaned financial transactions (2021 – 2023).
2. Total Allocated Budget: $796.11M  
3. Total Actual Spend: $891.20M
4. Net Variance: +$95.09M (+11.94% budget overrun across the period)

🧹 Data Cleaning & Preparation: Missing Data Handling: 
1. Identified and resolved null values within Category and Region attributes.
2. Type Casting: Formatted dates into standard YYYY-MM-DD and numerical spend fields into currency/decimal formats. 
3. Derived DAX Metrics: Variance: {Actual Spend} - {Budget Amount}
                     Variance (%): {Variance}(%) = {Variance}/{Budget Amount} * 100
4. Data Integrity: Removed duplicates and validated payment method values (Card, Bank Transfer, Cash, UPI).

📈 Key Visuals & Insights
1. KPI Cards:
   Instant metrics showing Total Budget, Total Actual Spend, and Variance %.  
2. Departmental Variance Breakdown:
   Highest Variance: Marketing (+15.12% overrun) and HR (+13.19% overrun).
   Lowest Variance: Finance (+8.39% overrun).  
3. Yearly Spending Trends (2021 – 2023)
   2021: Spend exceeded budget by $30.94M.
   2022: Peak expenditure year with a $36.52M overrun.
   2023: Improved budget control, lowering variance to $27.63M.  
5. Regional & Category Analysis:
   Evaluates spending distribution across 5 key regions (North, South, East, West, Central) and core expense categories (Salaries, Travel, Infrastructure,            Utilities, Training, Marketing).  
12. Payment Channel Breakdown:
     Visualizes transaction distribution across Card, Bank Transfer, Cash, and UPI.
    
🚀 How to Use / View the Project: 
1. Clone or download this repository. 
2. Open the .pbix or .pbit file in Power BI Desktop.
3. Use the top slicers to filter data dynamically by Department, Region, or Year.
