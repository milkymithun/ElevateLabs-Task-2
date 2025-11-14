📊 Superstore Overview Dashboard (Power BI)
Interactive Business Performance Report – Built Using Flat Files
📝 Project Summary

This Power BI dashboard provides a complete overview of Superstore performance from 2014–2017, using flat file data sources (CSV/Excel).
It highlights Sales, Profit, Orders, Regional Trends, Monthly Trends, Product Insights, and Customer Performance in a clean and interactive layout.

📂 Data Source

Loaded directly into Power BI using:
Home → Get Data → Text/CSV

🔧 Data Cleaning (Power Query)

Performed the following steps:

Removed duplicates

Corrected data types (Date, Number, Text)

Created Month, Year, Quarter columns

Calculated Profit Margin field

Handled missing values

Standardized column formats

🏗 Dashboard Sections
1️⃣ KPIs (Top Tiles)

Total Sales – 2.30M

Total Profit – 0.29M

Profit Margin – 12.47%

Total Orders – 1334

These KPIs give a quick snapshot of overall business performance.

2️⃣ Sales by Region (Donut Chart)

Shows the percentage contribution from:

1. West

2. East

3. Central

4. South

Helps identify high-performing and low-performing regions.

3️⃣ Sales by Product Name (Bar Chart)

Highlights top-selling products based on total sales value.
Useful for product performance, profitability, and supply planning.

4️⃣ Monthly Sales Trend (Line Chart)

Displays sales movement across months.
Helps identify seasonal spikes (March, September, November) and low-selling periods.

5️⃣ Top Customers (Table)

Shows:

1. Customer Name

2. Total Sales

3. Profit Margin

4. Order Count

Helps identify key customers contributing the most value.

6️⃣ Slicers Used

1. Sub-Category

2. Quarter

These allow users to slice data across product categories and time periods.

🖱 Report-Level Tooltips Implemented
A. Sales by Region Tooltip

Displays when hovering over any region segment:

1. Total Sales

2. Total Profit

3. Profit Margin

4. Total Orders

Helps compare regions beyond just percentage share.

B. Monthly Sales Tooltip

Shows additional information on hover:

1. Monthly Profit

2. Profit Margin

3. Total Orders

Gives deeper insight into monthly performance.

C. Sales by Product Tooltip

Displays for each bar:

Product Name

1. Total Profit

2. Quantity Sold

3. Discount Percent

Helps understand profitability and discount impact per product.

📊 Key Insights from the Dashboard

West region contributes the highest share of revenue.

Some top-selling products still show negative profit due to high discounts.

Monthly sales peak in March, September, and November.


├── Superstore_Dashboard.pbix
├── Flat Files (CSV/Excel)
└── README.md


Certain customers significantly drive business value.

South region needs attention due to lower sales and orders.
