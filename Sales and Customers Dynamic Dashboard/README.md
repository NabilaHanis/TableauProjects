# 🪑 Sales & Customer Dynamic Dashboard


## 📚 Case Study
N Company is a regional office supply retailer serving customers across multiple regions in the United States. The company offers a wide range of office products and furnishings, including desks, chairs, tables, office equipment, bookcases, storage solutions, binders, labels, envelopes, and other workplace essentials.

The client requested the development of an interactive dashboard that provides a comprehensive view of key sales metrics and performance trends. The dashboard is designed to help stakeholders evaluate year-over-year sales performance, identify emerging trends, analyze customer purchasing behavior, and support data-driven business decisions.


## 📌 Table of Contents
- [Business Context and Objectives](#business-context-and-objective)
- [Key Requirements](#key-requirements)
- [Data Wrangling](#data-wrangling)
- [Data Visualization](#data-visualization)
- [Business Insights and Recommendations](#business-insights-and-recommendations)
- [Thank you](#thank-you)


## 💡 Business Context and Objectives
The primary goal of this visualized dashboard is to enable N company to transform operational and sales data into actionable business insights. This dashboard is ultimately drive revenue growth and profitability by providing real-time visibility.


### Objectives:
- The Dashboard should allow clients to check historical data by offering them the flexibility to select any desired year.
- Provide clients with the ability to navigate between the dashboards easily.
- Make the charts and graphs interactive, enabling clients to filter data using the charts.
- Allow clients to filter data by product information such as category and subcategory
- Allow clients to filter data by product information such as location information like region, state and city.
- Provide clients with the ability to navigate between the dashboards easily


## 🎯 Key Requirements
- KPI Overview
-	Customers and Sales Trends 
-	Product subcategory comparison 
-	Yearly and Monthly trends for both Sales and Profit 
-	Customer Distribution by Number of Orders
-	Top 10 Customers By Profit
-	Year-over-year performance
-	Product subcategory comparisons
-	High-value customers and profit drivers
-	Interactive and Dynamic Data Filters


## 🔍 Exploratory Data Analysis (EDA) and  Data Preprocessing
In Tableau, **dimensions are qualitative** categorical fields that describe data, while **measures are quantitative** numerical fields that can be calculated and aggregated. Hence, these are the list of dimension and measure values used on this dashboard:

| Dimensions  | Measures |
| ------------- | ------------- |
| Date (Month)  | Sales  |
| Date (Year) | Profit  |
| Order ID  | Quantity  |

### Main Parameter 
Date (Year) has been chosen as the global variable across the dashboard. By allowing the user to select any year, the dashboard become interactive and dynamically change the visual data without affecting the underlying code. 
<br>
![Year Parameter](https://github.com/NabilaHanis/TableauProjects/blob/d6696e14f0f4d1bdee88fc6b10ef738dd95c7326/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Parameter%20%5BSelect%20Year%5D.png)

<br>

Observing how the data changes when user interact with the parameter (drop down menu) between the year 2024 and 2025
![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Quality%20Assurance%20Sales%20and%20percentage%20Diff%20for%202024%20Year%20Parameter.png) 
![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Quality%20Assurance%20Sales%20and%20percentage%20Diff%20for%202025%20Year%20Parameter.png)

/
/

### Profit Percentage Differences
![Profit % Diff](https://github.com/NabilaHanis/TableauProjects/blob/bc8f0c885fc13383a77ffe4a34986646d575f6ef/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Profit%20Percentage%20Differences.png)

![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Quality%20Assurance%20Sales%20and%20percentage%20Diff%20for%202024%20Year%20Parameter.png)
![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Quality%20Assurance%20Sales%20and%20percentage%20Diff%20for%202025%20Year%20Parameter.png)

/
/


### Profit Mix and Max Values
![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Profit%20Min%20and%20Max.png)

![](https://github.com/NabilaHanis/TableauProjects/blob/9a43832de06dc1e43de94e441980971b3aa9afaa/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Data%20testing%20with%202024%20Year%20Parameter.png)
![](https://github.com/NabilaHanis/TableauProjects/blob/d188f2385cdf1baa1299b7e0ebc94525c847378f/Sales%20and%20Customers%20Dynamic%20Dashboard/img/Data%20testing%20with%202025%20Year%20Parameter.png)
/
/

### Profit Average KPI
![KPI Profit AVG](https://github.com/NabilaHanis/TableauProjects/blob/54ca7b4c9b0692a4773b2901cabaff09ff8ff679/Sales%20and%20Customers%20Dynamic%20Dashboard/img/KPI%20Profit%20AVG.png)

### Filters

## 📊 Data Visualization

### Sales Dashboard
![Sales Dashboard](https://github.com/NabilaHanis/TableauProjects/blob/5c723b6bbcc2fc35efa6119778cff8b0c433780a/Sales%20and%20Customers%20Dynamic%20Dashboard/img/SalesDashboard-NCompany.png)

### Customer Dashboard
![Customer Dashboard](https://github.com/NabilaHanis/TableauProjects/blob/037b65ca54ecb67f02fc0c198fef81b204f4bea9/Sales%20and%20Customers%20Dynamic%20Dashboard/img/CustomerDashboard-NCompany.png)
\
\
Please Feel free to explore and interact with the dashboard on my [Tableau Public](https://public.tableau.com/app/profile/nabila.hanis/viz/SalesCustomersDynamicDashboard/SalesDashboard)


## 📝 Business Insights and Recommendations
-	Customer Insights
-	Total customers with YoY trend
-	Sales per customer (efficiency)
-	Order distribution per customer
-	Top 10 customers by profit with recent activity
-	Sales Insights
-	Total sales, profit, and quantity with trendlines
-	Sales vs. profit comparison across subcategories
-	Weekly trends showing spikes, slumps, and averages
-	Dynamic Filters for Deep Exploration



## ⭐ Thank you
Thank you for your time and interest. Please feel free to reach out to me if you have any questions  

-End of Note by Nabila Hanis-
