

<h1 align="center">📊 Interactive Sales Dashboard (Tableau)</h1>

<p align="center">
  A modern, interactive dashboard built in Tableau to explore customer shopping patterns, analyze KPIs, and uncover sales insights using visual and dynamic filters.
</p>

<p align="center">
</p><img width="1919" height="1079" alt="Screenshot 2025-11-05 235850" src="https://github.com/user-attachments/assets/467ae9a3-b58d-43a5-9ce1-6aa3f0fc45ba" />


---


## 🧾 Project Overview

This Tableau project transforms raw retail transaction data into a clean, intuitive, and fully interactive sales dashboard.  
Users can click charts to trigger real-time filtering, enabling smooth exploration of categories, payment modes, demographics, and time-based trends.

The dashboard is designed with a **clean visual hierarchy**, thoughtful spacing, and easy-to-read components for a strong overall user experience.

---

## 📁 1. Data Source and Preparation

| Detail | Description |
| :--- | :--- |
| **Dataset** | *Customer Shopping Data* (CSV) |
| **Fields Included** | Invoice Number, Customer ID, Gender, Age, Category, Quantity, Price, Payment Method, Invoice Date, Shopping Mall |
| **Calculated Measure** | `Sales = Price × Quantity` |
| **Data Cleaning** | Removed null values; ensured accuracy across sheets |
| **Data Types** | Measures standardized for correct aggregation |


---

## 📊 2. KPI Overview

The dashboard highlights four essential KPIs:

- **Total Sales**  
- **Total Quantity Sold**  
- **Total Invoices**  
- **Average Order Value (AOV)**  
  `AOV = Total Sales ÷ Total Invoices`


---

## 📈 3. Visualizations

Each sheet is built using clear Measure-by-Dimension analysis.

| Sheet | Chart Type | Purpose |
| :--- | :--- | :--- |
| **Sales by Mall** | Bar Chart | Ranks malls by revenue |
| **Sales by Payment Mode** | Pie Chart | Shows payment preference contribution |
| **Sales by Gender** | Pie Chart | Highlights gender-wise spending patterns |
| **Sales by Category** | Tree Map | Displays category performance by tile size |
| **Sales Trend (Monthly)** | Line Chart | Reveals month-wise sales movement |

---

## 🎨 4. Dashboard Layout & Design

The UI focuses on clarity, structure, and a visually friendly experience.

### Layout

- Built using **vertical + horizontal containers** for precise alignment  
- KPIs placed at the top for immediate understanding  
- Visual grouping for easier navigation  

### Style Decisions

- Clean blue title bar for identity  
- Soft light-gray background for reduced visual strain  
- White chart cards for contrast  
- Spaced components for breathing room  
- Border + padding to maintain structure  

### UX Highlights

- Logical grouping of visuals  
- Consistent typography hierarchy  
- Clear visual focus on KPIs  
- Smooth scanning through layout flow  

---

## 🧭 5. Interactivity

The dashboard supports fully dynamic filtering:

- Every chart can function as a **global filter**
- Clicking a bar, pie slice, tree map tile, or line point updates:
  - KPI cards  
  - All other charts  
- Enables fast drill-down into:
  - Mall performance
  - Payment behavior
  - Gender segmentation
  - Category strength
  - Monthly trends

This creates a fluid, dashboard-wide storytelling experience.

---

## ✅ 6. Project Outcomes

This dashboard demonstrates:

- Clean and validated data preparation  
- Effective KPI modeling  
- A polished Tableau design system  
- Strong visual storytelling  
- Interactive exploration through “Use as Filter”  
- A well-balanced UI and intuitive UX structure  

Built as a portfolio-ready, employer-friendly project showcasing real dashboarding skills.

---


