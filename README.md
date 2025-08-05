# Coffee Dashboard
Author: Janani Karthikeyan
Tool: Microsoft Excel (Pivot Tables, Charts, Dashboard)

📌 Overview
This Excel-based dashboard provides a comprehensive view of coffee sales across various states, channels, customer types, and timeframes. It is built to support business insights and decision-making by analyzing key performance indicators such as customer ratings, peak hours, and sales distribution.

📊 Data Sources & Sheets
1. sales_data
The core dataset containing raw transactional records, including:

Date, Time, State, Coffee Type

Sales Channel, Price, Payment Method

Customer Type, Wait Time, Order Rating

Special Requests, Promotions, Barista

2. Pivot Tables
Used to summarize key metrics:

pivot_rating: Average rating per coffee or category.

pvt_sales_channel: Sales breakdown by channel (e.g., Online, In-Store, App).

pvt_customer_type: Performance by customer segments (New, Returning, Tourist).

pivot_maps: Likely contains location-based summaries (e.g., state-wise).

pivot_busy_hours: Identifies peak sales hours.

3. Dashboard
The main interactive visual sheet pulling insights from pivot tables via:

Bar charts

Maps (if any visual mapping was implemented)

KPIs (e.g., Avg. Wait Time, Top Coffee, Revenue by Channel)

🎯 Key Insights Enabled
Most popular coffee types

Peak operating hours and busiest days

State-level performance breakdown

Customer satisfaction and wait time impact

Sales channel performance (Online vs In-Store vs App)

✅ Usage Instructions
Open the file in Microsoft Excel (recommended version: Excel 2016 or newer).

Navigate through the sheets:

Explore sales_data for raw records.

Use Dashboard for high-level summaries.

Refresh pivot tables if the raw data is updated.

Right-click on a pivot > Refresh.

