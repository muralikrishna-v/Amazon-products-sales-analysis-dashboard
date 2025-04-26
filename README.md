# 📊 Amazon Sales Analysis | Power BI Dashboard

## 📝 Project Overview
This project focuses on creating **interactive, business-driven dashboards** for a leading e-commerce brand using **Power BI**.  
The goal was to provide **deep insights** into Amazon product sales performance and Amazon Prime content engagement, enabling smarter, data-backed decisions.

Two fully designed dashboards were developed:
- **Sales Analysis | Amazon Products**
- **Sales Analysis | Amazon Prime**

Both dashboards offer **real-time visual insights** into sales trends, top-performing products/movies, customer reviews, and category analysis.

---

## 🔥 Key Objectives
- Monitor **Year-to-Date (YTD)** and **Quarter-to-Date (QTD)** product sales performance.
- Analyze **Amazon Prime** movie sales and review activity.
- Identify **top products/movies** by sales and customer reviews.
- Enable business users to **filter, slice, and drill down** data flexibly.
- Transform **raw sales and review data** into **clear, actionable visualizations**.

---

## 🛠️ Data Model and Structure

The solution uses three main tables with a clear relational model:

| Table | Purpose |
|:------|:--------|
| **Amazon_Data** | Holds Amazon product sales, prices, categories, shipments, and reviews. |
| **Amazon Prime Data** | Contains Amazon Prime movie sales, quality, movie types, directors, reviews. |
| **Calendar Table** | Custom date table for time intelligence (month, quarter, year analysis). |

**Relationships:**
- `Amazon_Data` → `Calendar Table`: *Order Date* to *Date* (Many-to-One)
- `Amazon Prime Data`: Independent table, analyzed separately.

📷 **Data Model Snapshot:**  
![Data Model Preview](https://github.com/muralikrishna-v/Amazon-products-sales-analysis-dashboard/blob/main/Screenshot%202025-04-27%20011449.png)

---

## 📈 Dashboards & Visuals

### 1. 📦 Amazon Product Sales Dashboard

**KPIs:**
- **YTD Sales**: Monitor overall revenue performance.
- **QTD Sales**: Track quarterly sales fluctuations.
- **YTD Products Sold**: Analyze product movement.
- **YTD Reviews**: Assess customer feedback volume.

**Charts:**
- **YTD Sales by Month** (Line Chart): Track monthly seasonal patterns.
- **YTD Sales by Week** (Column Chart): Understand week-to-week sales trends.
- **Sales by Product Category** (Heatmap): Visualize category-level revenue.
- **Top 5 Products by YTD Sales** (Bar Chart): Spotlight high-revenue products.
- **Top 5 Products by YTD Reviews** (Bar Chart): Spotlight most-reviewed products.

📷 **Dashboard Preview:**  
![Amazon Product Dashboard](https://github.com/muralikrishna-v/Amazon-products-sales-analysis-dashboard/blob/main/Screenshot%202025-04-27%20011335.png)

---

### 2. 🎬 Amazon Prime Analysis Dashboard

**KPIs:**
- **Total Sales**: Overall sales via Amazon Prime services.
- **Total No of Movies**: Library size available to customers.
- **Total No of Reviews**: Customer engagement level.

**Charts:**
- **Total Movie Counts by Release Year** (Line Chart): Understand content age distribution.
- **Total Sales by Movie Type** (Bar Chart): Discover genre performance.
- **Top 5 Movies by Total Sales** (Bar Chart): Identify blockbuster titles.
- **Top 5 Movies by Total Reviews** (Bar Chart): Highlight most engaging content.

📷 **Dashboard Preview:**  
![Amazon Prime Dashboard](https://github.com/muralikrishna-v/Amazon-products-sales-analysis-dashboard/blob/main/Screenshot%202025-04-27%20011309.png)

---

## ⚙️ Tools & Technologies Used
- **Power BI Desktop** (for dashboard development)
- **Excel** (for data cleaning and preparation)
- **Power Query** (for ETL transformation)
- **DAX (Data Analysis Expressions)** (for KPIs and calculated columns)

---

## 🚀 Skills Demonstrated
- Business Intelligence & Dashboard Design
- Data Analysis and Visualization
- KPI Tracking and Data Storytelling
- Data Modeling and Relationship Building
- UX/UI Design for Analytics Solutions

---

## 🛠 Challenges Addressed
- 📚 Integrated multiple datasets from different sources seamlessly.
- ✅ Ensured high data quality and accuracy.
- 🔒 Maintained privacy standards while handling review and customer data.
- 🎯 Delivered clean, dynamic, and business-readable reports.

---

## 📌 Conclusion
This project showcases how **effective data storytelling using Power BI** can uncover business opportunities, **optimize operations**, and **enable faster strategic decision-making**.  
The dashboards are **designed for executives**, **analysts**, and **business managers** to drive better, faster, smarter decisions.

---

## 📬 Let's Connect!
If you found this project valuable or would like to collaborate, feel free to reach out:

- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/muralikvasantha/)
- 📧 Email: **[muralikrishnavasanthavmk@gmail.com]**

---


