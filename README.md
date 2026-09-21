# 🚲 Bike Sales Analysis using Microsoft Excel

## 📌 Project Overview

This project is an **Excel-based Bike Sales Analysis** designed to explore customer demographics, purchasing behavior, income levels, commute distances, and other factors influencing bike purchases.

The project includes **data cleaning, formula-based data transformation, pivot table analysis, and an interactive dashboard** to present key insights in an easy-to-understand format.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze customer demographics and purchasing behavior.
* Identify patterns among customers who purchased bikes.
* Analyze bike purchases based on **age brackets**.
* Compare the **average income** of customers based on bike purchase status and gender.
* Analyze the relationship between **commute distance and bike purchases**.
* Create a dashboard to present important findings visually.
* Practice Excel formulas, Pivot Tables, data analysis, and dashboard creation.

---

## 📊 Dataset

The dataset contains customer-level information including:

* Customer ID
* Marital Status
* Gender
* Income
* Number of Children
* Education
* Occupation
* Home Ownership
* Number of Cars
* Commute Distance
* Region
* Age
* Age Bracket
* Purchased Bike

The dataset contains **1,000 customer records** used for the analysis.

---

## 🛠️ Tools & Techniques Used

### Microsoft Excel

The project was developed entirely using Microsoft Excel.

Key techniques used:

* Data Cleaning
* Data Transformation
* **IF & Nested IF Statements**
* Pivot Tables
* Conditional Analysis
* Data Aggregation
* Dashboard Creation
* Charts & Visualizations

---

## 🧮 Excel Formulas

One of the important parts of this project was creating an **Age Bracket** using nested `IF` statements.

Example:

```excel
=IF(L2>51,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
```

This formula categorizes customers into:

* **Adolescent** – Age below 31
* **Middle Age** – Age 31–51
* **Old** – Age above 51

Nested IF statements were used to transform raw customer age data into meaningful categories that could then be used for further analysis.

---

## 📑 Workbook Structure

The Excel workbook contains multiple sheets:

### 1. `bike_buyers`

Main dataset containing customer information and the calculated Age Bracket.

### 2. `Dashboard`

Interactive dashboard presenting the major findings from the analysis through visualizations.

### 3. `Avg Income`

Analysis of average customer income based on:

* Gender
* Bike Purchase Status

### 4. `Sheet4`

Analysis of bike purchases across different **Age Brackets**.

### 5. `Customer Commute`

Analysis of bike purchases based on **Customer Commute Distance**.

---

## 📈 Key Analysis

### Age Bracket Analysis

The analysis categorizes customers into different age groups and compares their bike purchasing behavior.

| Age Bracket | Bike Not Purchased | Bike Purchased |
| ----------- | -----------------: | -------------: |
| Adolescent  |                 71 |             39 |
| Middle Age  |                292 |            344 |
| Old         |                156 |             98 |

### Average Income Analysis

The project also compares average income between customers who purchased a bike and those who did not, segmented by gender.

This helps identify income-related patterns within the customer base.

### Customer Commute Analysis

Customer commute distance was analyzed to understand how distance from home to work may relate to bike purchasing behavior.

---

## 📊 Dashboard

The project includes a dedicated **Bike Sales Dashboard** that summarizes the analysis through visualizations and allows the findings to be interpreted more easily.

The dashboard focuses on customer characteristics and purchasing behavior to provide a concise overview of the dataset.

---

## 💡 Skills Demonstrated

This project demonstrates practical experience with:

* Microsoft Excel
* Data Cleaning
* Data Transformation
* Nested IF Formulas
* Logical Functions
* Pivot Tables
* Data Analysis
* Customer Segmentation
* KPI/Metric Analysis
* Dashboard Development
* Data Visualization
* Business Insights

---

## 🚀 Project Purpose

This project was created as a practical **Data Analytics portfolio project** to demonstrate how Excel can be used to transform raw customer data into meaningful business insights through formulas, structured analysis, Pivot Tables, and dashboards.

---

## 📁 Files

* `Excel Project Dataset.xlsx` – Complete Excel analysis workbook
* `README.md` – Project documentation

---

## 👨‍💻 Author

**Mohd Zaid Khan**

Data Analytics | Excel | SQL | Data Visualization
