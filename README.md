# Elevate_Labs_DA_Internship_Task3_Sales_Dasboard

# Elevate Labs Data Analyst Internship - Task 3: Sales Dashboard Design

## Project Overview

This repository contains the deliverables for Task 3 of the Elevate Labs Data Analyst Internship. The primary goal was to design and develop an interactive sales dashboard in Power BI, focused on providing key business insights and actionable recommendations from a sales dataset.

## Objective

The objective of this task was to create a comprehensive and interactive dashboard that enables business stakeholders to:
* Monitor key performance indicators (KPIs) at a glance.
* Analyze sales and profit trends over time.
* Identify performance drivers and areas for improvement (e.g., profitable vs. unprofitable segments/products).
* Facilitate data exploration through interactive filters and navigation.
* Summarize critical findings and recommendations in a concise presentation.

## Dataset

* **Dataset Used:** `Task_1_Superstore_Sales_Data_Cleaned.xlsx` (specifically, the raw `Sample - Superstore.csv` sheet within it)
* **Description:** This dataset contains detailed sales transaction records for a hypothetical superstore, including information on sales, profit, quantity, discount, product categories, customer segments, order dates, and geographical data. It was previously cleaned and prepared in Task 1.

## Tools Used

* **Power BI Desktop:** For data modeling, dashboard design, visualization, and interactivity.
* **Microsoft PowerPoint:** For creating the summary presentation of key insights and recommendations.

## Dashboard Features & Design Highlights

The Power BI dashboard is designed with user-friendliness and actionable insights in mind:

* **Key Performance Indicators (KPIs):**
    * **Total Sales:** Overall revenue generated.
    * **Total Profit:** Net financial gain/loss, with **conditional formatting** to highlight positive (Green) vs. negative (Red) performance.
    * **Sales Year-over-Year (YoY) Growth %:** Measures sales growth against the previous year to track business momentum.
* **Time-Series Analysis Visuals:**
    * **Sales and Profit Trend Over Time (Line and Clustered Column Chart):** Visualizes the historical performance of sales and profit, revealing trends, seasonality, and periods of divergence.
* **Detailed Performance Breakdowns:**
    * **Profit by Product Category (Clustered Column Chart):** Identifies the profitability of different product categories, highlighting top performers and critical loss-making areas (e.g., Furniture).
    * **Sales by Customer Segment (Clustered Bar Chart):** Shows revenue contribution from different customer segments.
    * **Sales vs. Profit Relationship (Scatter Chart):** Plots individual transactions to reveal the correlation between sales and profit, effectively identifying high-volume, low-profit, or unprofitable outlier orders. Includes `Quantity` as bubble size and animates over `Order Date` using the `Play Axis`.
* **Interactive Elements:**
    * **Slicers:** Allow users to dynamically filter data by `Order Date`, `Product Category`, `Customer Segment`, `Region`, etc., enabling custom data exploration.
    * **Navigation Menu (Bookmarks):** Implemented using custom buttons and Power BI Bookmarks to provide seamless navigation between different report pages (e.g., Executive Summary, Sales Trends, Profitability Analysis).
* **Design Principles:**
    * Applied a consistent color theme for visual coherence.
    * Ensured clear titles and labels for all visuals.
    * Optimized layout with sufficient whitespace for readability.

## Key Business Insights & Recommendations

Based on the dashboard analysis, the following critical insights and actionable recommendations have been identified:

* **Profitability Crisis in Growth:** Despite consistent year-over-year sales growth, overall profitability is significantly challenged, culminating in a current cumulative loss of **-$20.9K**.
* **Unprofitable Furniture Category:** The Furniture category consistently generates losses, severely impacting overall profit.
* **High-Volume, Low-Profit Transactions:** The scatter plot reveals several high-sales orders that yield minimal or negative profit, indicating potential issues with discounting or associated costs.
* **Dominant Consumer Segment:** The Consumer segment is the largest sales contributor, requiring continued strategic focus.

**Actionable Recommendations:**
* **Deep-Dive into Furniture:** Conduct an urgent review of Furniture category's cost structure, pricing, and discount policies.
* **Optimize Large Orders:** Analyze high-sales, low-profit orders to refine discount practices and identify cost inefficiencies.
* **Strategic Segment Engagement:** Maintain focus on the Consumer segment while exploring growth opportunities within other segments (e.g., Home Office).
* **Continuous Monitoring:** Utilize the interactive dashboard for ongoing performance tracking and rapid decision-making.

## How to Use the Dashboard

1.  **Download:** Clone this GitHub repository to your local machine.
2.  **Open Power BI:** Ensure you have Power BI Desktop installed.
3.  **Load:** Open the Power BI report file: `Task_3_Dashboard_Design.pbix`
4.  **Interact:** Explore the data using the slicers, drill-down options, and navigation buttons. Click the 'Play' button on the scatter chart to see trends over time.

## Deliverables

* `Task_3_Dashboard_Design.pbix`: The interactive Power BI Desktop report file.
* `Task_3_Interactive Dashboard Design & Analysis.pdf`: The PowerPoint presentation summary (exported to PDF) of key insights and recommendations.
* `Task_3 Power BI Visual Report Interactive Dashboard.pdf`: A PDF export of the complete Power BI dashboard pages.
* `Task_1_Superstore_Sales_Data_Cleaned.xlsx`: The cleaned dataset used as input for the Power BI dashboard.
* `Dashboard_Screenshots/`: A folder containing high-resolution screenshots of the key dashboard pages. (Make sure to create this folder and place your images inside).

## Dashboard Screenshots

*(It's highly recommended to include screenshots of your main dashboard pages here for a quick visual overview. Replace the placeholders with actual links to your images once uploaded to the `Dashboard_Screenshots` folder.)*

---

**[Screenshot 1: Sales Trends Page]**
`![Sales Trends](dashboard_screenshots/Sales and Profit Trend Over Time.PNG)`

**[Screenshot 2: Profitability Analysis Page]`**
`![Profitability Analysis](dashboard_screenshots/Profit by Product Category & Sub Category.PNG)`

---

## My Learning & Experience

This task provided invaluable experience in designing an end-to-end interactive dashboard. Key learnings include:
* Mastering Power BI's visualization capabilities for various analytical needs (KPIs, trends, distributions, relationships).
* Implementing interactive elements like slicers, bookmarks, and play axis for dynamic data exploration.
* Leveraging conditional formatting to highlight critical business insights effectively.
* Developing data storytelling skills by translating complex data into clear, actionable recommendations for stakeholders.

---
