### Swiggy Food Delivery — Sales Analytics Dashboard
An end-to-end Excel analytics project built on real-world-style Swiggy order data. 
This project covers the full analyst workflow — from raw data to a fully interactive
dashboard — and was designed to demonstrate hands-on skills in data cleaning, pivot 
table analysis, KPI design, and business intelligence reporting.
_______________________________________________________________________________________
### Project Overview
Swiggy is one of India's largest food delivery platforms. This project analyses 
197,430 food orders placed across 28 Indian states between January and August 2025, 
covering 993 restaurants and hundreds of food categories.
The goal was simple: take a raw transactional dataset and turn it into something a
business team could actually use — a clean, interactive dashboard that answers real 
questions about sales performance, customer behaviour, and city-level demand.
_______________________________________________________________________________________
### Dashboard Preview
_______________________________________________________________________________________
### File Structure
Swiggy_Raw_Data_Excel_Dashboard.xlsx
│
├── Swiggy Data          → Raw transactional dataset (197,430 rows)
├── Swiggy KPI Design    → KPI calculations and pivot-based analysis
└── Swiggy Dashboard     → Interactive visual dashboard with slicers
_______________________________________________________________________________________
### Dataset Details
The raw dataset contains 197,430 order records with the following 14 columns:
Column	Description
State	Indian state where the order was placed
City	City of the order
Order Date	Date of the transaction
Day	Day of the week (Mon–Sun)
Quarter	Financial quarter (Q1, Q2, Q3)
Week No	Week number (1–36)
Restaurant Name	Name of the restaurant
Location	Locality within the city
Category	Food category / menu section
Dish Name	Specific dish ordered
Food Type	Veg or Non-Veg
Price (INR)	Order value in Indian Rupees
Rating	Customer rating for the order
Rating Count	Number of ratings received
Coverage:
•	Date Range: January 2025 – August 2025 (36 weeks, 3 quarters)
•	Cities: 28 cities across India
•	States: 28 states including Karnataka, Maharashtra, Delhi, Telangana, Uttar Pradesh, 
  and more
•	Restaurants: 993 unique restaurants
•	Food Types: Veg and Non-Veg
__________________________________________________________________________________________
### Key KPIs
These five headline metrics were calculated from the raw data and displayed prominently 
on the dashboard:
KPI	Value
Total Sales	₹ 53.01M
Average Rating	4.34
Average Order Value	₹ 268.51
Total Ratings Count	5.59M
Total Orders	197,430
___________________________________________________________________________________________
### Analysis Performed
1. Sales by Food Type
Non-Veg orders dominate, accounting for 65% of total sales (₹34.6M), while Veg orders
contribute 35% (₹18.4M). This was visualised using a donut chart to give a clean proportional view.
3. Monthly Sales Trends
Sales remained consistently strong throughout the year, ranging between ₹6.3M and
₹6.8M per month. February saw a slight dip to ₹6.3M, but March–August held steady
— suggesting a loyal and consistent customer base with no major seasonal drop-off.
5. Quarterly Performance
Quarter	Total Sales	Avg Rating	Total Orders
Q1 (Jan–Mar)	₹19.7M	4.34	73,100
Q2 (Apr–Jun)	₹19.9M	4.34	74,200
Q3 (Jul–Aug)	₹13.4M	4.34	50,200
Q2 edges out Q1 slightly in both sales and orders. Q3 is lower because the data only covers
July–August (2 months vs 3).
7. Daily Sales Trends
Saturday is the highest-earning day at ₹7.78M, followed by Sunday at ₹7.64M — confirming the
classic weekend food delivery pattern. Monday and Tuesday are the slowest days, which aligns
with typical consumer behaviour.
Day	Sales
Mon	₹7.45M
Tue	₹7.36M
Wed	₹7.54M
Thu	₹7.66M
Fri	₹7.58M
Sat	₹7.78M
Sun	₹7.64M
9. Weekly Sales Trends
A week-by-week breakdown across 36 weeks revealed consistent performance, with minor peaks around
 certain weeks. Sales held mostly between ₹1.3M–₹1.6M per week, showing platform stability with
no major outlier weeks.
11. Top 5 Cities by Sales
City	Sales
Bengaluru	₹5.46M
Lucknow	₹3.12M
Hyderabad	₹3.02M
Mumbai	₹3.02M
New Delhi	₹2.83M
Bengaluru is the clear leader — nearly double the sales of the second-ranked city — reflecting
its status as India's tech and dining capital.
13. Sales by State (Geographic Map)
A Bing-powered geographic map was used to visualise state-level sales distribution across India.
 Karnataka leads at ₹5.5M, followed by Maharashtra at ₹3.0M and Telangana at ₹3.0M. States in
the northeast and central regions show comparatively lower volumes.
_________________________________________________________________________________________________
### Tools & Techniques Used
Area	Details
Tool	Microsoft Excel
Data Volume	197,430 rows × 14 columns
Pivot Tables	Used for all aggregations — sales by food type, city, state, day, week, quarter
Charts	Donut chart, bar charts, line chart, geographic map, summary table
Slicers	Month, Food Type, and Category filters — all connected to the dashboard
KPI Cards	Designed with custom formatting to display headline metrics prominently
Map Visual	Bing Maps integration for state-level geographic distribution
Data Cleaning	Ensured consistent date formats, standardised food type labels, handled null ratings
__________________________________________________________________________________________________
### Dashboard Features
The dashboard is fully interactive. You can filter the entire view by:
•	Month — Jan through Sep (individual or multi-select)
•	Food Type — Veg, Non-Veg, or both
•	Category — Filter by specific food category (e.g., Biryani, Sweets, Chinese)
All charts, KPI cards, the quarterly table, and the map update together when a slicer selection 
is changed — giving a complete, connected view of any subset of the data.
__________________________________________________________________________________________________
### Business Insights
A few things that stood out after digging into the data:
1.	Non-Veg dominates but Veg is not far behind. At 35%, Veg orders are a substantial segment
2.	worth targeting with dedicated promotions.
3.	Ratings are uniformly high. An average of 4.34 across all three quarters — with zero variation
4.	— suggests either very consistent service quality, or that the rating distribution warrants
5.	further investigation (potential rating inflation).
6.	Weekends are the revenue peak. Saturday–Sunday consistently outperform weekdays. Promotions
7.	and offers timed around weekends would likely see higher conversion.
8.	Bengaluru is in a league of its own. At ₹5.46M it accounts for roughly 10% of all platform sales.
9.	Understanding what drives Bengaluru's volume — restaurant density, order frequency, or higher
10.	AOV — would be valuable.
11.	Average Order Value is ₹268. This sits in the mid-range for food delivery. There's likely an
12.	opportunity to push AOV higher through bundling or upselling, particularly on weekday orders
13.	where basket sizes tend to be smaller.
___________________________________________________________________________________________________
### How to Use This File
1.	Download Swiggy_Raw_Data_Excel_Dashboard.xlsx
2.	Open in Microsoft Excel (2016 or later recommended for full slicer and map support)
3.	Navigate to the Swiggy Dashboard sheet
4.	Use the slicers on the left panel to filter by Month, Food Type, or Category
5.	All charts and KPIs will update automatically
____________________________________________________________________________________________________
### Author
Shubham Dhainje Data Analyst · MSc Data Science (Distinction), University of Essex, UK 
____________________________________________________________________________________________________
### Note
This project was built as part of a data analytics portfolio to demonstrate end-to-end Excel skills 
including data wrangling, pivot analysis, KPI design, and interactive dashboard development. 
The dataset is structured to reflect realistic food delivery order patterns.
____________________________________________________________________________________________________

