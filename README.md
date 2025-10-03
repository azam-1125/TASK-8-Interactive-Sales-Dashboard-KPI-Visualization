# TASK 8: Interactive Sales Dashboard & KPI Visualization

## 🎯 Objective

The primary objective of this task was to design and develop a comprehensive **Interactive Dashboard** using the Superstore dataset. The goal was to visualize key performance indicators (KPIs), identify major sales trends, and uncover regional/segment performance discrepancies to support business decision-making.

## 🛠️ Tools and Methodology

* **Dataset:** `Superstore.csv`
* **Visualization Tool:**  Power BI
* **Methodology:**
    1.  **Data Preparation:** Handled missing values, ensured data types were correct, and prepared the date and geographical fields for time-series and map visualization.
    2.  **KPI Calculation:** Defined and calculated core business metrics: **Total Sales**, **Total Profit**, **Profit Ratio** (`Profit / Sales`), and **Average Order Value**.
    3.  **Visualization Design:** Utilized various chart types including **time-series line charts** for sales trends and **treemaps/bar charts** for category breakdown.
    4.  **Interactivity:** Implemented Year filter and Quarter filter to enable dynamic data exploration.

## 📊 Key Insights from the Dashboard

1.  **Profitability Crisis:** Despite high revenue, the **Central region** exhibits the lowest Profit Ratio and the highest number of negative-profit transactions, particularly in **Texas** and **Illinois**.
2.  **Product Performance:** **Office Supplies** drive the highest sales volume, but the **Furniture** category frequently results in losses, often due to low-profit, high-cost sub-categories like **Tables**.
3.  **Shipping Impact:** The **Standard Class** shipping mode is utilized most often but is not the most profitable. Priority shipping options often correlate with higher profit margins.
4.  **Sales Seasonality:** Sales volume and profit consistently peak during the **fourth quarter (Q4)**, particularly in the months of **November and December**, indicating effective year-end campaigns.
5.  **Customer Segment Value:** The **Corporate** segment is consistently profitable and offers the highest **Average Order Value**, making it a prime focus for B2B strategy.

## 📁 Deliverables

* **`Superstore_Dashboard.pbix`:** The final interactive dashboard file.
* **`Dashboard_Screenshot.png`:** A static image.
* **`Superstore.csv`:** The source data file.
