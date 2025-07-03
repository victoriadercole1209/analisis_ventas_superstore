# 📊 Superstore Sales Analysis (2014–2017)

This project presents an in-depth business intelligence analysis of retail operations using the **Superstore dataset**, covering the period from **2014 to 2017**. The goal is to identify key sales patterns, profitability trends, customer segmentation insights, and product performance across multiple regions in the United States.

## 📁 Project Structure

- `Superstore.xlsx`: Normalized and cleaned dataset used for modeling and analysis.
- `Superstore_PowerBI.pbix`: Interactive Power BI dashboard for deep data exploration.
- `Análisis de ventas del Superstore.pdf`: Full project report (in Spanish) with detailed methodology, SQL modeling, DAX measures, and conclusions.

---

## 🎯 Project Objective

To deliver actionable insights on the commercial strategy and profitability of a retail company using Power BI. The analysis is aimed at empowering decision-making for pricing, product strategy, logistics optimization, and customer segmentation.

---

## 🧰 Tools & Technologies

- **Microsoft Excel**: Data cleaning and preprocessing  
- **SQL Server**: Data modeling (ER diagram)  
- **Power BI**: Data visualization and interactive dashboards  
- **DAX (Data Analysis Expressions)**: Custom KPIs and calculated metrics  

---

## 🧪 Key Hypotheses Analyzed

1. **Seasonal Sales Trends**: Are there peak months (e.g., holidays, Black Friday)?
2. **Top-Selling Products**: Do a few products account for most of the revenue?
3. **Customer Segmentation Impact**: Do certain customer segments contribute disproportionately to revenue?
4. **Promotional Effectiveness**: Do discounts lead to increased revenue or profits?

---

## 📊 Dashboard Highlights

The Power BI report includes the following views:

- **Sales Overview**: Annual revenue trends, state-wise sales distribution, sales by category and segment.
- **Geographic Analysis**: Profit heatmaps, monthly demand, and regional performance.
- **Customer Analysis**: Sales by customer segment, top clients, and demand by product category.
- **Product Performance**: Top products and subcategories by volume and profit.
- **Shipping Preferences**: Insights into most-used shipping methods by region.
- **ToolTips**: Contextual pop-ups for detailed product, region, and year-over-year insights.

---

## 📐 Data Modeling

The project follows a **star schema** design with the following key tables:

- `TB_Superstore`: Central fact table with transactional data  
- Dimension tables: `TB_Category`, `TB_Subcategory`, `TB_City`, `TB_Region`, `TB_Segment`, `TB_Ship Mode`, etc.  
- Calendar Table: Used for time intelligence and period comparison metrics  

---

## 📏 Key Metrics (DAX Measures)

- `Total Sales`, `Total Profit`, `Average Sales`, `Monthly Demand`
- `Year-over-Year Sales Growth`
- `Unique Customers`, `Cities Covered`
- Sales by year (`Sales 2014`, `Sales 2015`, etc.)

---

## 🧠 Insights & Conclusions

- **Sales peaks** were identified in **July** and **October**, with regional variation.
- High-demand products include **Chairs**, **Phones**, and **Storage solutions**.
- The **West region** leads in profitability.
- Customer segmentation reveals a few key clients dominate purchasing.
- Promotions showed varying effects depending on region and product.

---

## 🔭 Future Work

- Deep dive into customer behavior and loyalty metrics.
- Incorporate external data (economic trends, competitor performance).
- Explore geographic influence on buying patterns using geospatial analytics.

---

## 📚 Data Source

Superstore Dataset by Vivek468:  
[https://www.kaggle.com/datasets/vivek468/superstore-dataset-final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## 👩‍💼 Author

**María Victoria D’Ercole**  
Business Intelligence & Data Analysis Project (2025)
