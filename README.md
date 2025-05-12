# 🚗 Car Sales Analysis BI Dashboard

A Business Intelligence dashboard analyzing year-to-date (YTD) car sales performance. Built using Power BI, the dashboard provides interactive insights across regions, brands, body styles, and customer demographics.

---

## 📁 Dataset Overview

**Columns:**

- `Car_id` : Unique identifier for each sale  
- `Date` : Transaction date  
- `Customer Name` : Name of the customer  
- `Gender` : Gender of the customer  
- `Annual Income` : Customer's annual income  
- `Dealer_Name` : Name of the dealer  
- `Company` : Car manufacturer (e.g., Ford, Toyota)  
- `Model` : Car model  
- `Engine` : Engine details  
- `Transmission` : Manual / Automatic  
- `Color` : Car color  
- `Price ($)` : Sale price in USD  
- `Dealer_No` : Dealer ID  
- `Body Style` : SUV, Sedan, etc.  
- `Phone` : Customer contact number  
- `Dealer_Region` : Geographic region of dealer  

---

## 📊 KPIs (Year-to-Date)

```text
🟢 YTD Total Sales      : Total revenue generated YTD
🟡 YTD Average Sales    : Average sale value YTD
🔵 YTD Cars Sold        : Total number of units sold YTD

---

## 📈 Visual Reports

- 📆 **YTD Sales Weekly Trend**  
  Line chart showing weekly revenue trends throughout the year.

- 🚙 **YTD Total Sales by Body Style**  
  Bar chart displaying revenue distribution across different car body styles (e.g., Sedan, SUV).

- 🎨 **YTD Total Sales by Color**  
  Visual breakdown of total sales based on car color preferences.

- 🌍 **YTD Total Sales by Dealer Region**  
  Regional analysis of car sales performance across various dealer regions.

- 🏢 **Company-Wise Sales Trends**  
  Trend chart showing sales performance for each car manufacturing company over time.

---

## 🛠️ Tools & Technologies Used

```text
🔹 Power BI Desktop      : Data modeling, dashboard development, and visualizations
🔹 Microsoft Excel/CSV   : Data source file used for importing car sales data
🔹 DAX                   : Used for creating custom KPIs and calculated fields
