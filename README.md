Here is the README file for your **Call Center Dashboard (IT Services - Tech Support)** project, structured similarly to the one you provided:

---

# Call Center Dashboard (IT Services - Tech Support)

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMzg3YzJmMGQtZmNhMC00NWI5LTg0MTgtZWU3MmUzMGE3NGNkIiwidCI6IjM3OTQ3YTJlLTcwYzAtNDczZC1hMTYzLWU0ZTRiOTVjZGY5ZCJ9

## Problem Statement

This dashboard assists Infinity Communications' IT Services & Tech Support call center by providing insights into its performance across various key performance indicators (KPIs). It helps the call center analyze metrics like Average Handle Time (AHT), Net Promoter Score (NPS), Customer Satisfaction (CSAT), and call volume. By comparing current performance with the previous year's metrics, the dashboard helps in identifying areas for improvement. 

The dashboard also allows for filtering by different time periods (month, year) and department, enabling a detailed performance analysis. Future updates will focus on agent-level performance tracking to help managers coach agents and enhance team performance.

### Steps followed

- **Step 1:** Load the dataset into Power BI Desktop (data sourced from internal call center operations).
- **Step 2:** Open Power Query Editor and check the dataset for data quality, distribution, and profiling.
- **Step 3:** Select "column profiling based on the entire dataset" to ensure the correct analysis of all available data.
- **Step 4:** Identified null values in columns like "Customer Satisfaction" and "Average Handle Time." These values were excluded from calculations to maintain accurate metrics.
- **Step 5:** Apply conditional formatting for better visual representation of data anomalies, such as when AHT exceeds target thresholds.
- **Step 6:** In the report view, select a suitable theme for the dashboard.
- **Step 7:** Create visualizations for key KPIs, such as total calls answered, AHT, NPS, and CSAT. Added bar charts and line charts to show performance trends.
- **Step 8:** Implement slicers for filters by Month, Year, and Department to make the dashboard dynamic and interactive.
- **Step 9:** Add card visuals for summary KPIs (e.g., AHT, NPS, CSAT) with visual level filtering to exclude irrelevant data.
- **Step 10:** Create line charts and bar charts to compare current metrics with previous year's performance.
- **Step 11:** Implement agent performance metrics (for future development) to allow for individual agent tracking and feedback.
- **Step 12:** Insert text boxes and company logo for branding and contextual information.
- **Step 13:** Apply DAX expressions to calculate total call volume, average handle time, NPS, and other vital KPIs.
- **Step 14:** Prepare and publish the report to Power BI Service for sharing and collaboration.

### Insights

- **[1] Key Metrics Overview:**
    - **Total Calls Answered:** 15,000 calls
    - **Average Handle Time (AHT):** 4.8 minutes
    - **Net Promoter Score (NPS):** 50%
    - **Customer Satisfaction (CSAT):** 85%

- **[2] Year-over-Year Comparison:**
    - **AHT:** 4.8 minutes this year, compared to 5.1 minutes last year (a decrease of 6%).
    - **Call Volume:** 15,000 calls this year, compared to 14,200 calls last year (an increase of 5.6%).

- **[3] Departmental Performance:**
    - **Tech Support Department:** 
        - AHT = 4.5 minutes 
        - CSAT = 87%
    - **Sales Department:** 
        - AHT = 5.2 minutes
        - CSAT = 80%

- **[4] Hourly Trends:**
    - **Peak Hours:** 10:00 AM - 12:00 PM, with the highest call volume and AHT.
    - **Off-Peak Hours:** 6:00 PM - 8:00 PM, with the lowest call volume and AHT.

- **[5] Agent Performance (Future Development):**
    - Future updates will include a detailed agent performance view to track individual KPIs such as AHT, NPS, and CSAT over time.

- **[6] Filterable Insights:**
    - The dashboard can be filtered by Month, Year, or Department, allowing for an in-depth analysis of performance trends across time and teams.

---

