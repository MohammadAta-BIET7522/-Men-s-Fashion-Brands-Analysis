🧵 Men’s Fashion Brands Analysis – Power BI Dashboard
By Insight BI Solution Private Limited
📌 Project Overview

This project presents a complete Power BI dashboard for analyzing the performance of Men’s Clothing Brands across multiple business KPIs such as sales, pricing, profitability, discounts, and product variety.

The dashboard provides decision-makers with actionable insights into:

*Top-performing brands
*Low-performing brands
*Pricing behavior
*Discount and profit trends
*Product variety contribution
*Category-wise brand distribution

The report is designed with a premium fashion theme, maintaining a clean dark-gold UI consistent with the retail fashion industry.

🎯 Key Business Questions Answered

✔ Which are the Top 5 Brands by:

*Highest Average Discount %
*Highest Average Profit %
*Highest Average Sales Price
*Highest Number of Varieties

✔ Which brands show lowest profit performance?
✔ What does the brand distribution look like across the dataset?
✔ Are premium brands pricing consistently higher than regular brands?

📊 Dashboard Preview

This section provides a visual preview of the Power BI dashboard built for Men’s Fashion Brand Analysis.
The report consists of multiple pages containing:

*Top-performing and under-performing brands
*Average discount %, profit %, and sales price analysis
*Product variety distribution
*Brand availability catalog
*Custom-branded dark–gold UI (Insight BI)

These visuals give users a quick understanding of the insights generated and the analytical depth of the project.

📈 Key Insights Generated

⭐ Top 5 Brands by Discount %

*NETPLAY
*U.S Polo Assn
*THE BEAR HOUSE
*British Club
*The Indian Garage Co

⭐ Top 5 Brands by Profit %

*Crown Threads
*IDENTITI
*Lonexo
*Ramadhani Cloth
*Tyzlo

⭐ Top 5 Brands by Average Sales Price

*ARMANI EXCHANGE
*BROOKS BROTHERS
*Terra Luna
*SCOTCH & SODA
*Kingdom of White

⭐ Top 5 Brands by Varieties

*The Indian Garage Co
*U.S. Polo Assn
*NETPLAY
*SNITCH
*GAP

⚠ Bottom 5 Brands by Profit %

*URBANO FASHION
*LERIYA FASHION
*SHOWOFF
*SURHI
*SiliSoul

🛠 Tools & Technologies Used
Tool	Purpose

*Power BI Desktop	Data cleaning, modeling, and dashboard creation
*DAX	KPI calculations & measures
*Power Query	Data transformation
*Excel/CSV Dataset	Data source for analysis

🧩 Data Model

*Brand Name
*Category
*Sales Price
*Profit Percentage
*Discount %
*SKU Varieties
*Product Type
*Revenue
*Cost

The data model is optimized with star-schema principles for better performance.

🧮 Important DAX Measures Used
*Avg Discount % = AVERAGE('Data'[Discount])
*Avg Profit % = AVERAGE('Data'[Profit %])
*Avg Sales Price = AVERAGE('Data'[Sales Price])
*Variety Count = DISTINCTCOUNT('Data'[Product Name])
*Top 5 Brands = TOPN(5, VALUES('Data'[Brand]), [Avg Sales Price], DESC)

🎨 Design & UI

*Modern dark navy theme
*Gold typography inspired by fashion industry standards
*Custom brand logo “Insight BI”
*Balanced layout focusing on storytelling
*Clean fonts for easy readability

🚀 How to Use This Dashboard

*Download the .pbix file from this repository
*Open it in Power BI Desktop
*Refresh the dataset if needed
*Navigate through the report pages to explore insights

🌐 Use Cases

This project is ideal for:

*Fashion Retail Analytics
*E-commerce Performance Tracking
*Brand Performance Insights
*Marketing & Merchandising Decisions
*Pricing Strategy Optimization

💼 About the Author
Mohammad Ata
Passionate about Data Analyst, Data Visualization, and Insight-Driven Decision Making.

⭐ If you like this project — please ⭐ star the repo!

It helps support more Power BI dashboards like this.
