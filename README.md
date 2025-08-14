# Power BI AdventureWorks Dashboard

Business intelligence project created as part of my Data Science studies, based on the **AdventureWorks2022** dataset.  
The goal was to design an interactive Power BI report with **at least three report pages**, each presenting relevant business insights, while ensuring high usability and applying advanced Power BI features.

---

## Project Objectives
- Present key sales insights across products, customers, territories, and time.
- Build a user-friendly and visually appealing dashboard with multiple pages.
- Apply advanced Power BI functionality for deeper interactivity.

---

## Features Implemented
- **Multiple fact table model (fact constellation)** using `FactSalesOrderDetail` and `FactSalesOrderHeader`.
- Shared dimension tables (Date, Product, Customer, Sales Territory, Sales Person, Special Offer, Sales Reason).
- **Advanced Power BI features** included:
  - Custom drill-down hierarchy (non-date)
  - Drill Through navigation
  - Conditional formatting
  - Custom Tooltips
  - Map visualization
  - Year-over-year comparison with DAX
  - Mobile layout optimization
  - Clickable URLs in visuals
  - Custom theme with consistent color palette for visual identity.

---

## Report Pages
1. **Dashboard Overview** – KPIs, sales trends, top products, and territory map.
2. **Products & Customers** – Best-selling products, customer ranking, and category analysis.
3. **Sales Territories & Salespersons** – Territory performance, salesperson metrics, and detailed drill-through.
4. **Feature Overview** – Documentation of advanced Power BI features used in the report, with visual examples.


---

## Data Model
- Existing AdventureWorks data model provided in the assignment, used without altering the underlying table structure.
- Fact constellation schema with two main fact tables sharing multiple dimension tables.

---

## Key Insights
- North America is the leading sales territory.
- Road Bikes category generates the highest revenue.
- Peak sales occur during summer months.
- A small number of customers contribute a large portion of total sales.

---

## Download and Open the Report

👉 [power_bi_adventure_works.pbix](./power_bi_adventure_works.pbix)  

You can open the file in **Power BI Desktop**.

---

## Demo Preview  
<br>

### Dashboard  
![Overview](images/1_overview.png)  
<br>

### Products 
![Products & Customers](images/2_products_customers.png)  
<br>

### Store & Sales Person  
![Time Analysis](images/3_time_analysis.png)  
<br>

### Feature Overview  
![Sales Territories](images/4_sales_territories.png)  
<br>

---

## Author  

**Lence Majzovska**  
*Data Science Student @ EC Utbildning 2025*  
