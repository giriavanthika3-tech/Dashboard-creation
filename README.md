*Visualizing Airline Performance: A Comprehensive Power BI Dashboard for Profitability, Revenue, and Regional Operations.*
---

### **Project Overview**
This Power BI dashboard provides an operational and financial analysis for an airline company. The dashboard takes raw data regarding cities, states, product categories (Type1, Type2, Type3), and financial metrics (Profit, Revenue) and transforms it into an interactive, visual story. It allows stakeholders to monitor high-level performance while drilling down into specific sub-categories and geographical details.

---

### **Objective**
The primary objective of this dashboard is to empower airline executives and operations managers to:
1.  **Track Financial Health:** Monitor total profit and revenue streams across different service sub-categories.
2.  **Optimize Regional Strategy:** Understand the scale of operations by tracking the number of cities and states served.
3.  **Identify Performance Drivers:** Analyze how different categories contribute to overall profitability to inform pricing and inventory decisions.

---

### **Dashboard Features**
*   **KPI Cards:** Quick-glance summary cards showing the total Count of City (786), Count of State (811), and Sum of Profit (1.76M).
*   **Donut Chart (Unit Price Analysis):** A breakdown of unit prices by Sub-Category, showing nearly equal distribution (approx. 32% - 35% each) between Type1, Type2, and Type3.
*   **Small Multiples Grid (Average Quantity):** A 2x2 panel displaying line charts to compare the average quantity sold across Categories (A, B, C, D), separated by Sub-Category (Type1, 2, 3).
*   **Gauge Chart:** A visually striking gauge indicating the Sum of Profit (1.76M) relative to a maximum target of 3.53M.
*   **Step Chart (Profit & Revenue):** A dual-axis step chart that visualizes both Profit (left axis) and Revenue (right axis) by Category and Sub-Category, highlighting peaks and valleys across the operational spectrum.
*   **Horizontal Bar Chart:** A comparative ranking of the Sum of Profit by the primary Category (A, B, C, D), showing both raw values and percentage contributions.

---

### **Business Questions**
1.  Which Category (A, B, C, or D) generates the highest total profit and revenue?
2.  How does the average quantity sold differ between different types of products (Type1 vs. Type2 vs. Type3) across different categories?
3.  What is the overall utilization of profit capacity compared to the goal (3.53M)?
4.  Are we operating in a wide enough geographical area (States/Cities) to support our profit margins?
5.  Does a higher unit price in a specific sub-category correlate with higher profitability?

---

### **Key Insights**
*   **Leading Profit Generator:** **Category C** is the star performer, generating a total profit of **494.39K**, making up 100% of the highest tier in the horizontal comparison.
*   **Profit vs. Revenue Gap:** By looking at the dual-axis step chart, we can identify distinct gaps. For example, under Category A, **Type3** hits the highest revenue peak (**375K**), yet the profit margins fluctuate significantly compared to other Types, indicating potential cost differences.
*   **Steady Unit Pricing:** The donut chart reveals a balanced pricing strategy. Type2 holds the largest share of unit price at 35.20%, closely followed by Type3 at 32.89% and Type1 at 32.71%. This indicates a deliberate tiered pricing structure.
*   **Performance Gap:** The gauge chart shows the current Profit at **1.76M**, which is roughly **50%** of the 3.53M target. This signals that there is significant room for growth to double the current profitability.
*   **Quantity Variations:** In the small multiples grid, Category A, Type1 shows a sharp decline in average quantity (from roughly 9.8 to under 9), while Category D, Type2 shows a sharp increase (from ~9.2 to 12.04). These are areas requiring operational investigation.

---

### **Tools & Technologies**
*   **Power BI Desktop:** Used for creating the data model, visualizations, and formatting.
*   **DAX (Data Analysis Expressions):** Used to create calculated measures (like the KPI sums and percentage calculations).
*   **Power Query (M Language):** Assumed to be used for cleaning, transforming, and shaping the raw airline datasets before loading.
*   **Data Source:** Likely an Excel spreadsheet or CSV file containing airline operation metrics.

---

### **Skills Demonstrated**
*   **Data Visualization:** Expert use of diverse charts (Gauge, Donut, Step-chart, Bar charts, Small Multiples) to tell a complex story simply.
*   **Dashboard Design & UI/UX:** Effective use of a cohesive color palette (earthy oranges and browns), clear headers, and grid alignment for ease of reading. Custom branding (Airline logo) is integrated seamlessly.
*   **Business Intelligence:** Ability to translate raw numbers into actionable business KPIs.
*   **Analytical Thinking:** Connecting disparate views (Quantity vs. Price vs. Profit) to offer holistic insights rather than isolated metrics.
*   **Dual-Axis Visualization:** Skillfully implementing dual axes on the step chart to allow comparison of two different value scales (Profit vs. Revenue) simultaneously.

---

### **Business Value**
*   **Strategic Decision Making:** By visualizing which categories and sub-categories are most profitable, leadership can allocate more resources (marketing budget, inventory stock) to **Category C** while investigating the high-revenue/low-profit anomalies in **Category A**.
*   **Goal Alignment:** The gauge chart serves as a constant visual reminder of the 3.53M profit goal. It acts as a motivational tool, showing the team they are currently at ~50% of their target.
*   **Operational Efficiency:** Insights on average quantity trends allow supply chain managers to ensure they aren't overstocking in Categories with declining sales (Category A, Type1) and are well-supplied in emerging demand areas (Category D, Type2).
*   **Geographic Scaling:** The KPI cards (786 Cities, 811 States) prove a massive operational footprint. The business can use this as a benchmark to decide if they want to consolidate to cut costs, or expand further to chase the 3.53M profit ceiling.
