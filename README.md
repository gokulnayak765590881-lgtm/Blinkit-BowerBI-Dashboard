# Blinkit Analysis Dashboard (Power BI)

##  Project Overview
This project performs a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. By transforming raw retail data into an interactive Power BI dashboard, I identified key optimization opportunities for outlet management and product placement.

##  Key Insights & KPIs
The dashboard tracks four primary **Key Performance Indicators (KPIs)**:
* **Total Sales:** Overall revenue generated ($1.20M).
* **Average Sales:** Average revenue per transaction ($141).
* **Number of Items:** Total count of unique products sold (8,523).
* **Average Rating:** Customer satisfaction score (3.9/5.0).

## Visualizations Included
* **Sales by Fat Content:** Analyzed the impact of 'Low Fat' vs 'Regular' products on total revenue (Donut Chart).
* **Item Type Performance:** Identified top-performing categories like Fruits, Snacks, and Household items (Bar Chart).
* **Outlet Establishment Trend:** Evaluated how the age of an outlet influences its revenue growth (Line Chart).
* **Geographic Analysis:** Mapped sales distribution across Tier 1, 2, and 3 cities (Funnel Map).
* **Outlet Size & Type:** Comparison of Supermarket vs. Grocery store efficiency (Matrix/Stacked Column Chart).

## Technical Workflow
1.  **Data Cleaning:** Used **Power Query** to handle missing values (Item Weight) and standardize categorical labels (e.g., fixing "LF" to "Low Fat").
2.  **Data Modeling:** Created a Star Schema for efficient filtering.
3.  **DAX Calculations:** Developed custom measures for Average Sales, Total Items, and conditional formatting logic.
4.  **Dashboard Design:** Implemented a modern dark-themed UI with interactive slicers for real-time filtering.

## 📁 Repository Structure
├── Data/                 # Raw .csv or .xlsx dataset
├── Dashboard/            # Blinkit_Sales_Analysis.pbix file
├── Screenshots/          # Images of the dashboard pages
└── README.md             # Project documentation
