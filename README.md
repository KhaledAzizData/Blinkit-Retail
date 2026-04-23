# Blinkit Sales Performance Analysis
**Grocery Retail Analytics & Outlet Performance Dashboard**

## 📌 Project Overview
This project delivers a comprehensive analysis of **Blinkit's** sales performance, customer satisfaction, and inventory distribution. By processing retail transactional data, I developed a Power BI dashboard to identify high-revenue product categories and evaluate the operational efficiency of various outlet types and sizes across different geographic tiers.

---

## 📈 Key Numerical Insights

### 1. Overall Performance Metrics
* **Total Revenue:** Generated **$1.20M** in total sales across the entire outlet network.
* **Average Rating:** Maintained a consistent customer satisfaction score of **3.9 / 5.0**.
* **Item Volume:** Managed a diverse inventory, with the highest volume of items (**6,913**) achieving a solid **4.0 rating**.

### 2. Product & Consumer Trends
* **Top Revenue Drivers:** * **Fruits & Vegetables:** $0.18M
    * **Snack Foods:** $0.18M
    * **Household Items:** $0.14M
* **Health-Conscious Pivot:** **Low Fat** items significantly dominate the market share, accounting for **$776.32K (64.7%)** of total sales, compared to **$425.36K** for regular fat content.

### 3. Outlet & Operational Performance
* **Revenue by Outlet Size:** * **Medium:** $0.51M (Top Performer)
    * **Small:** $0.44M
    * **High:** $0.25M
* **Establishment Trends:** Identified a historical sales peak in **2018 ($0.20M)**, with a steady baseline of **$0.13M** maintained through **2022**.
* **Geographic Tiers:** Tier 3 locations emerged as the primary volume driver for the business.

---

## 🛠 Tech Stack & Skills
* **Power BI:** Developed interactive dashboards with a focus on UX and clean data storytelling.
* **DAX (Data Analysis Expressions):** Created custom measures for **Total Sales**, **Average Ratings**, and **Item Counts**.
* **Data Modeling:** Linked item identifiers with outlet characteristics to perform multi-dimensional analysis.
* **Advanced Visualization:** * **Donut Charts:** For Fat Content distribution.
    * **Area Charts:** For temporal sales growth (2011–2022).
    * **Decomposition Trees:** For rating-to-item type breakdowns.

---

## 🧩 Analytical Challenges Solved
* **KPI Centralization:** Consolidated fragmented retail data into a single-pane-of-glass view for executive decision-making.
* **Filter Logic:** Implemented dynamic slicers for **Outlet Size**, **Location Type**, and **Item Type** to allow for granular regional audits.
* **Visibility Analysis:** Correlated **Item Visibility** and **Item Weight** (from raw data) against total sales to identify shelf-space efficiency.

---

## 🚀 Repository Structure
```text
├── data
│   └── blinkit_sales_data.csv    # Raw transactional data
├── dashboards
│   └── blinkit_main.pbix         # Power BI Dashboard file
└── README.md                     # Project documentation
