# Sales-Management-Project-in-PowerBI

## Define Business Request

### Message from Sales Manager

I hope you are doing well. We need to improve our **internet sales reports** and want to move from static reports to **visual dashboards**.
Essentially, we want to focus on how much we have **sold of what products**, to **which clients** and how it has been **over time**.
Seeing as each **salesperson** works on different customers it would be beneficial to be able to **filter** them also.
We measure our numbers against **budget** so l added that in a spreadsheet so we can compare our values against performance.
The budget is for 2021 and we usually look **2 years back** in time when we do analysis of sales.


### Analyze Requirement using User Stories

<img width="715" alt="Screenshot 2023-07-30 at 15 58 32" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/6ba7c779-8010-4197-9981-93cbdb1217d1">

* Necessary Systems: PowerBI, CRM system


### Clarify Details
Provide a dashboard in PowerBI, including 2 pages: 
- Page 1: Sales Overview, including:
  + KPI chart
  + Filters by Year and Month (Slicer)
  + Filters by Customer City, Sub-category, Category, Product Name (Slicer)
  + Sales by Product Category (Donut chart)
  + Sales and Budget by month (Line chart)
  + Sales by top 10 Customers, top 10 Products (Bar chart) 
- Page 2: Customer Details, including:
  + Filters by Year and Month (Slicer)
  + Filters by Customer City, Sub-category, Category, Product Name (Slicer)
  + Sales and Budget total sales (Card)
  + Sales and Budget by month (Line chart)
  + Sales by top 10 Customers (Bar chart)
  + Sales per each customeres by month (Table)

_Suggest to add a map showing Sales by Customer City so that stakeholders have better understanding of sales by region_ 



## Data Model
<img width="914" alt="Screenshot 2023-07-28 at 18 54 47" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/5e39aabb-8327-46ac-a102-f8b8baf6978e">


## Dashboard

<img width="1027" alt="Screenshot 2023-07-28 at 00 01 50" src="https://github.com/ChloeM1515/PowerBI-project/assets/130263988/0a9d0b4f-7c97-49f0-be53-ccff24919c3a">


<img width="1027" alt="Screenshot 2023-07-28 at 00 02 11" src="https://github.com/ChloeM1515/PowerBI-project/assets/130263988/8e486d94-9311-4437-b04d-5114f278fdd6">


## Insights and Recommendation
(Data range from Jan 2019 - Jan 2021)



### Insight by best-sellers products:
<img width="277" alt="Screenshot 2023-07-30 at 16 13 05" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/38ecacac-2140-4ca8-a5b7-4e3825e19a38">


- Insight: Mountain Bikes 46, 42, 38 are **best-seller products** overall. However, best-seller in Jan 2021 was taken place by another product, Helmet.
- Recommendation: Focus on sales strategy for Mountain Bikes products, as well as conduct analysis for Helmet to see if it is the raising star in 2021.

### Insight by clients:
<img width="944" alt="Screenshot 2023-07-30 at 16 28 23" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/9a5ecd07-c615-426e-8c88-86bec4cc396e">

<img width="948" alt="Screenshot 2023-07-30 at 16 28 35" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/f0e44727-847e-48a9-973a-68d740243243">

<img width="803" alt="Screenshot 2023-07-30 at 16 28 49" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/cbf904f6-b2d9-4542-b580-0a46e9315d9c">

- Insight: **Jordan Turner** was in top 5 customers from 2019 - 2020. Others were new customers.
- Recommendation: Enhance customer service for top 10 customers like Jordan. Conduct further analysis on customer churn rate and retention rate.

### Insight by budget:
<img width="433" alt="Screenshot 2023-07-30 at 16 57 47" src="https://github.com/ChloeM1515/Sales-Management-Project-in-PowerBI/assets/130263988/16bb7f6e-76f2-4997-91d9-5381bb6ee7cb">

- Insight: Sales and Budget were quite close in 2020, except for significant differences in June and November 2020.
- Recommendation: Take futher investigation on sales in June and November to see if there was any cause to significant increase.
