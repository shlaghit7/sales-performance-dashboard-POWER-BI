# sales-performance-dashboard-POWER-BI
Interactive Power BI dashboard analyzing sales performance, revenue growth &amp; KPIs
# 📊 Sales Performance & Revenue Growth Dashboard

## 🚀 Project Overview

The **Sales Performance & Revenue Growth Dashboard** is a dynamic and interactive Business Intelligence solution developed using Power BI. This project focuses on analyzing sales performance, tracking revenue growth, and evaluating business KPIs to support data-driven decision-making.

The dashboard provides a **comprehensive view of business performance**, enabling stakeholders to monitor trends, identify opportunities, and improve overall sales strategy.

---

## 🎯 Objective

* To analyze sales data across regions, products, and channels
* To track key KPIs such as Revenue, Profit, Growth %, and Achievement %
* To compare Target vs Actual performance
* To provide actionable insights for business decision-making

---

## 🛠️ Tools & Technologies Used

* **Power BI** – Data Visualization & Dashboarding
* **Microsoft Excel** – Dataset Creation & Preparation
* **DAX (Data Analysis Expressions)** – KPI Calculations
* **Power Query** – Data Cleaning & Transformation

---

## 📂 Dataset Description

The dataset used in this project is a structured sales dataset containing over 100+ records with the following key fields:

* Date (Day-wise sales tracking)
* Region & City (Geographical analysis)
* Sales Executive (Performance tracking)
* Product Category & Product Name
* Units Sold & Selling Price
* Revenue, Cost, Profit
* Profit Margin %
* Customer Type (New / Existing)
* Sales Channel (Online / Offline)
* Target Sales & Actual Sales
* Achievement % & Growth %

---

## 🔄 Data Preparation (Power Query Steps)

The following steps were performed to clean and transform the data:

* Removed null and duplicate values
* Standardized column names
* Converted data types (Date, Currency, Percentage)
* Created Month, Quarter, and Year columns
* Calculated Revenue and Profit columns
* Formatted percentage fields for better readability

---

## 🧮 DAX Measures Implemented

Key DAX measures used in the dashboard:

* **Total Revenue** = SUM(Revenue)

* **Total Cost** = SUM(Cost)

* **Total Profit** = SUM(Profit)

* **Total Units Sold** = SUM(Units Sold)

* **Profit Margin %** = (Total Profit / Total Revenue) × 100

* **Achievement %** = (Actual Sales / Target Sales) × 100

* **Growth %** =
  ((Current Revenue – Previous Revenue) / Previous Revenue) × 100

---

## 📊 Dashboard Features

The dashboard is designed with a **clean corporate layout** and includes:

### 🔝 KPI Cards

* Total Revenue
* Total Profit
* Units Sold
* Achievement %
* Growth %

### 📈 Visualizations

* Revenue by Region (Column Chart)
* Monthly Revenue Trend (Line Chart)
* Sales Channel Distribution (Donut Chart)
* Product Category Performance (Bar Chart)
* Target vs Actual Sales (Clustered Chart)

### 📉 Data Table

* Matrix displaying Region-wise performance
  (Revenue, Profit, Achievement %)

### 🎛 Interactive Filters

* Region
* Product Category
* Sales Channel
* Sales Executive
* Month

---

## 🎨 Dashboard Design Highlights

* Corporate theme with clean UI
* Color coding:

  * 🟢 Green → Profit / Positive Growth
  * 🔴 Red → Underperformance
  * 🔵 Blue → Primary metrics
* Consistent fonts and alignment
* Interactive and user-friendly layout

---

## 📊 Key Business Insights

* Identifies top-performing regions contributing maximum revenue
* Highlights most profitable product categories
* Tracks whether sales targets are achieved or missed
* Analyzes growth trends over time
* Compares performance across sales channels

---

## 💼 Business Impact

This dashboard helps organizations to:

* Make data-driven decisions
* Improve sales strategies
* Optimize product performance
* Identify growth opportunities
* Monitor team and regional performance effectively

---

## 📸 Dashboard Preview

(Add your dashboard image here)

```markdown
![Dashboard Preview](dashboard.png)
```

---

## 📁 Project Structure

```
Sales-Performance-Dashboard/
│
├── Data/
│   └── Sales_Dashboard_Dataset.xlsx
│
├── Dashboard/
│   └── Sales_Performance_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
├── README.md
```

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Connect to dataset if needed
4. Explore dashboard using filters and visuals

---

## 🔗 GitHub Repository

(Add your repository link here)

## 📌 Future Enhancements

* Sales Forecasting using Power BI Analytics
* Drill-through pages for detailed insights
* Customer segmentation analysis
* Automated data refresh integration

## 🧠 Learning Outcomes

* Hands-on experience in Power BI dashboard creation
* Strong understanding of DAX and data modeling
* Improved analytical and business problem-solving skills
* Practical exposure to real-world BI projects

## 📢 Conclusion

This project demonstrates how raw data can be transformed into meaningful insights using Power BI. It highlights the importance of data visualization in modern business environments and showcases the ability to build professional, decision-oriented dashboards.

## 🙌 Acknowledgment

This project was created as part of a data analytics portfolio to demonstrate practical business intelligence skills.

