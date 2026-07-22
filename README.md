### 1. Project Overview
**Project Title:** Airline Operations Profit & Revenue Analysis Dashboard
**Description:** This dashboard provides a comprehensive visualization of an airline's operational performance. It focuses on analyzing financial metrics (Profit and Revenue) and operational logistics (Quantity and Pricing) across various geographical locations (Cities and States) and product/service sub-categories (Type1, Type2, Type3). The dashboard is designed to give stakeholders a quick, high-level view of financial health while allowing them to drill down into category-specific performance.

### 2. Objective
The primary objective of this project is to centralize disparate operational data into a single, interactive reporting tool. The specific goals include:
*   **Financial Visibility:** To monitor total profit generation and revenue trends.
*   **Category Performance Analysis:** To evaluate how different sub-categories (Type1, 2, 3) perform across different market segments (A, B, C, D).
*   **Geographic Assessment:** To track operational reach, measured by the number of distinct cities and states served.
*   **Strategic Decision Support:** To identify high-performing and underperforming categories to inform resource allocation and marketing strategies.

### 3. Dashboard Features
*   **Executive Summary KPI Cards:** Top-level metrics showing *Count of City* (786), *Count of State* (811), and *Sum of Profit* (1.76M) to give immediate context.
*   **Product Mix Analysis:** A Donut Chart displaying the *Sum of Unit Price by Sub-Category*, showing that all three sub-categories (Type1, 2, 3) have an almost equal 33.3% split in pricing.
*   **Cross-Category Trend Analysis:** A small-multiples line graph displaying the *Average of Quantity by Category and Sub-Category*. This allows for side-by-side comparisons of sales volume across categories A through D.
*   **Comprehensive Dual-Axis Step Chart:** The centerpiece of the dashboard is a combination chart showing *Sum of Profit* (primary Y-axis, left) and *Sum of Revenue* (secondary Y-axis, right) by Category and Sub-Category. The "step" visual is effective here because it clearly demarcates the financial boundaries between different sub-category groups.
*   **Category Ranking:** A horizontal bar chart ranking the *Sum of Profit by Category*. It clearly shows Category C is the most profitable, followed by A, D, and B.
*   **Performance Goal Gauges:** A prominent semi-circular gauge chart showing *Sum of Profit* reaching 1.76M against a maximum target/threshold of 3.53M (approx. 50% completion).

### 4. Business Questions
The dashboard is built to answer the following critical business questions:
1.  Which specific category (A, B, C, or D) generates the highest total profit, and which generates the lowest?
2.  Within each category, which sub-category (Type1, Type2, Type3) is driving the most profit or revenue?
3.  Is the pricing strategy consistent across all sub-categories, or are there significant deviations?
4.  Is there a direct correlation between the average quantity sold and the total profit generated for a given category?
5.  How close are we to hitting our company-wide profit target (3.53M)?

### 5. Key Insights (Data-Driven)
*   **Category C is the Financial Powerhouse:** Category C outperforms all others in Profit generation (494.39K), significantly higher than the lowest performer, Category B (417.76K).
*   **Revenue vs. Profit Disconnect:** While Category C has the highest Profit, Category A's "Type1" sub-category shows the highest single revenue spike (410K) on the step chart. This indicates that while Type1/A has high gross revenue, its margins might be lower than Type2/C.
*   **Balanced Product Mix:** The donut chart reveals a nearly perfect 33% distribution in unit pricing. This indicates that the airline's base pricing structure is heavily standardized across their core products.
*   **Volume Fluctuations:** The average quantity sold fluctuates significantly within categories (e.g., Category A sees a high of 10.66 units for Type2, but only 9.80 for Type1), highlighting inconsistent demand across specific offerings.

### 6. Tools & Technologies
*   **Primary Tool:** Microsoft Power BI Desktop
*   **Data Transformation:** Power Query (M Language) – used for cleaning, shaping, and merging underlying data sources (though invisible, it's implied).
*   **Data Modeling:** DAX (Data Analysis Expressions) – used to create calculated measures for *Sum of Profit*, *Sum of Revenue*, *Count of City*, and *Count of State*.
*   **Visualization Types:** KPI Cards, Donut Chart, Line Charts (Small Multiples), Step/Stepped Area Chart, Horizontal Bar Chart, and Gauge Chart.

### 7. Skills Demonstrated
*   **Data Visualization:** Choosing the right chart types (e.g., stepping charts for distinct categorical breaks, small-multiples for comparing trends).
*   **Dashboard Layout & UX:** Creating a clean, well-branded layout (using a consistent peach/mocha color palette) that logically groups related metrics together.
*   **DAX Calculation:** Proficiency in creating aggregations (SUM, COUNT) to power the visuals.
*   **Executive Storytelling:** The ability to condense large amounts of raw data into digestible summaries for executive stakeholders.
*   **Dual-Axis Charting:** Managing complex visuals that plot two different Y-axis scales simultaneously (Profit vs. Revenue).

### 8. Business Value
*   **Data-Driven Resource Allocation:** By identifying that Category C is the highest profit driver, management can shift marketing budgets and operational focus toward Type2 and Type3 offerings within that category.
*   **Pricing Strategy Validation:** The dashboard proves that current pricing is highly standardized. If future economic conditions change, this data provides a clear baseline to test whether altering the price on a specific sub-category boosts revenue without damaging volume.
*   **Target Identification:** The Gauge chart serves as a constant visual reminder that the company is currently at 1.76M profit against a 3.53M goal. This urgency can drive sales teams and operational managers to close the gap.
*   **Operational Efficiency:** By monitoring the "Average Quantity" metrics, management can spot dips in demand (e.g., Category B, Type3 dropping to 9.38) and investigate operational or market-specific reasons for the decline before it heavily impacts the bottom line.
