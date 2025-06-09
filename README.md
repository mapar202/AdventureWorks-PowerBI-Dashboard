# 💡 AdventureWorks Power BI Dashboard

This is a multi-page interactive dashboard built with Power BI, based on Microsoft's AdventureWorks sample database. It visualizes product performance, internet sales, and other key business areas using modern UX design and data storytelling principles.

## 📌 Project Overview

This Power BI project is a **multi-page dashboard** that offers insights into various segments of the AdventureWorks dataset, including:

- **Product Performance**
- **Internet Sales**
- **Customer Segments**
- **Reseller Sales**
- **Reseller Overview**
- **Employee Metrics**

The dashboard layout was designed using **Figma** to ensure a clean and user-friendly experience before implementation in Power BI.

🔄 **Note:**  
This is the **first version** of the dashboard. Future updates will add enhancements in visuals, user experience, and analytical depth.

---

## ✨ Features by Page

### 📦 Product Page

- Redesigned layout using Figma before building in Power BI for a more intuitive UX.
- Removed unused whitespace to provide more space for visual elements.
- Added **ranking in the stacked bar chart** to highlight top-performing products by Order Quantity.
- Created **a dynamic tooltip** to show the ranking of each product compared to the previous year.
- Included **interactive buttons** that change color dynamically when selected (UX improvement).
- Built **a custom tooltip** that displays which slicers are selected, helping users understand the filtered context.

### 🌐 Internet Sales Page

- KPI cards at the top include **dynamic Year-over-Year (YoY) comparison** vs. the previous year.
- Each KPI card includes **conditional formatting** to indicate growth or decline.
- Visuals include product revenue breakdown, order quantity by customer segments, profit flow, monthly revenue by country, and category-wise sales volume with profit margin trends (📊 see "Category-wise Sales Volume & Profit Margin" chart).
- Designed for both **business overview** and **granular drill-down** into internet sales insights.

---

## 🛠 Tools Used

- **Power BI**
- **Figma** – for planning and designing the layout
- **DAX** – for dynamic calculations and tooltips

---

## 📁 Folder Structure

```text
AdventureWorks-PowerBI-Dashboard/
│
├── assets/
│   └── dashboard-screenshots/
│       ├── product-page.png
│       └── internet-sales-page.png
│
├── pbix/
│   └── AdventureWorks_Dashboard.pbix
│
├── figma/
│   └── dashboard-design.fig
│
├── README.md
└── LICENSE (optional)
