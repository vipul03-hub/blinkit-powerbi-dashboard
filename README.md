# Blinkit Sales Dashboard

## Project Overview
This project is an interactive Power BI dashboard created to analyze Blinkit's sales performance across different outlet types, outlet locations, item categories, and customer ratings.

The dashboard helps identify:
- Top-performing outlet types
- High-selling product categories
- Sales trends over time
- Outlet performance by location and size
- Customer rating distribution

---

# Dashboard Preview

<img width="1042" height="612" alt="Screenshot 2026-05-15 130940" src="https://github.com/user-attachments/assets/0daa8777-0e70-4411-bbd7-7bdf29e99452" />


---

# Business Problem
Blinkit operates across multiple outlet locations and product categories.  
The objective of this dashboard is to help stakeholders:

- Monitor overall sales performance
- Identify profitable outlet types
- Understand customer preferences
- Analyze item category contribution
- Compare outlet performance across tiers and sizes

---

# KPIs Used

| KPI | Description |
|---|---|
| Total Sales | Overall revenue generated |
| Average Sales | Average sales per outlet/item |
| Number of Items | Total items sold |
| Average Rating | Average customer rating |

---

# Dashboard Features

## 1. Sales Overview
- Total Sales KPI
- Average Sales KPI
- Average Rating KPI
- Number of Items KPI

## 2. Outlet Establishment Trend
- Sales trend by outlet establishment year
- Helps identify growth patterns

## 3. Item Type Analysis
- Sales contribution by item category
- Comparison of product performance

## 4. Outlet Size Analysis
- Medium, Small, and High outlet comparison

## 5. Outlet Location Analysis
- Tier 1, Tier 2, Tier 3 sales comparison

## 6. Outlet Type Performance
- Supermarket and Grocery Store comparison
- Average sales and ratings analysis

## 7. Dynamic Filters
Users can filter dashboard by:
- Outlet Location Type
- Item Type
- Outlet Size

---

# Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

---

# DAX Measures Used

## Total Sales
```DAX
Total Sales = SUM(BlinkIT Grocery Data[Sales])
```

## Average Sales
```DAX
Average Sales = AVERAGE(BlinkIT Grocery Data[Sales])
```

## Average Rating
```DAX
Average Rating = AVERAGE(BlinkIT Grocery Data[Rating])
```

## Number of Items
```DAX
Number of Items = COUNT(BlinkIT Grocery Data[Item Identifier])
```

---

# Key Insights

- Tier 3 outlets generated the highest sales contribution.
- Fruits and Snacks categories contributed significantly to total revenue.
- Supermarket Type 1 achieved the highest overall sales.
- Medium-sized outlets performed better than small outlets.
- Customer ratings remained stable across outlet types.

---

# Future Improvements

- Add profit analysis dashboard
- Add customer segmentation
- Add forecasting using time series analysis
- Create mobile-friendly layout
- Add drill-through pages
- Improve dashboard responsiveness

---

# Repository Structure

```text
Blinkit-Sales-Dashboard/
│
├── data/
│   └── BlinkIT Grocery Data.csv
│
├── images/
│   └── <img width="1042" height="612" alt="Screenshot 2026-05-15 130940" src="https://github.com/user-attachments/assets/a3d16cd4-1fa9-49a0-928b-9f9e18a999f8" />

│
├── blinkit.pbix
│
└── README.md
```

---

# Conclusion
This dashboard provides a clear overview of Blinkit's sales ecosystem and helps in understanding outlet performance, product demand, and customer behavior using interactive visual analytics.

---

# Author
Vipul
