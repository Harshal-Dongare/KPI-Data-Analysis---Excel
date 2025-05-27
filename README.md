# Exploratory Data Analysis for Sales Operation using Excel

## Project Overview

An Excel-based data analysis project that evaluates key performance indicators (KPIs) for a retail or sales operation across five sales representatives (Jacob, Arnold, Naomi, David, Ariel) throughout 2023. Housed in `KPI-Project.xlsx`, it tracks monthly metrics including revenue, number of customers, new customers, customer acquisition costs (CAC), and revenue per customer, comparing actual performance against targets and previous-year data. Leveraging Excel’s data processing and visualization tools, the project provides actionable insights into sales trends, target achievement, and cost efficiency, showcasing proficiency in spreadsheet-based analytics.

## Dataset Description

The dataset is stored in `KPI-Project.xlsx`, with a single worksheet covering Q1–Q4 2023. It includes:

-   **Time Frame**: January–December 2023, organized by month and quarter.
-   **Entities**: Five sales representatives (Jacob, Arnold, Naomi, David, Ariel).
-   **Metrics** (per representative, per month):
    -   **Revenue**: Actual, target, and previous-year revenue.
    -   **Number of Customers**: Total customers served.
    -   **Number of New Customers**: Actual, target, and previous-year counts.
    -   **Customer Acquisition Costs (CAC)**: Total and per customer, with targets and previous-year data.
    -   **Revenue per Customer**: Actual, target, and previous-year values.
-   **Aggregates**: Totals for revenue, customers, new customers, and derived metrics (e.g., total revenue per year: $9,255,000; total new customers: 1,228).
-   **KPI Overview (Q4 2023)**:
    -   Revenue actual vs. target ($2,180,000 vs. $2,325,000; 93.76% achievement).
    -   New customers actual vs. target (309 vs. 300; 103% achievement).
    -   Average revenue per customer ($1,986.77 vs. $2,500 target; 79.47% achievement).
    -   Average CAC per customer ($372.11 vs. $333.33 target; 111.63% achievement).

## Project Structure

The analysis is contained in a single Excel file:

-   **`KPI-Project.xlsx`**:
    -   **Data Entry**: Monthly metrics for each representative, organized by quarter (Q1–Q4 2023).
    -   **Calculations**: Derived metrics (e.g., CAC per customer, revenue per customer) using Excel formulas.
    -   **Aggregations**: Totals and averages for key metrics, computed across representatives and months.
    -   **KPI Overview**: Summary table for Q4 2023, comparing actuals to targets with achievement percentages.
    -   **Visualizations**: (Assumed) Charts or tables visualizing revenue trends, target achievement, or CAC efficiency (based on typical Excel practices).

## Key Insights

-   **Revenue Performance**: Total revenue for 2023 was $9,255,000, with Q4 achieving 93.76% of the $2,325,000 target, indicating a slight shortfall.
-   **Customer Growth**: The project recorded 3,799 total customers and 1,228 new customers annually, with Q4 exceeding the new customer target (309 vs. 300; 103% achievement).
-   **Revenue per Customer**: Average revenue per customer was $2,436.17 annually, but Q4 fell short of the $2,500 target (79.47% achievement), suggesting room for upselling.
-   **Customer Acquisition Costs**: Q4 CAC per customer ($372.11) exceeded the $333.33 target (111.63% achievement), highlighting potential inefficiencies in acquisition strategies.
-   **Data Quality**: Consistent data across months enables reliable comparisons, though manual entry may introduce errors if not validated.

## How to Use

### Setup

-   **Requirements**: Microsoft Excel (2016 or later) or compatible spreadsheet software (e.g., Google Sheets).
-   Ensure `KPI-Project.xlsx` is accessible in your working directory.

### Execution

-   Open `KPI-Project.xlsx` in Excel or compatible software.
-   Navigate to the main worksheet to view monthly data, totals, and the Q4 KPI overview.
-   Review calculated metrics (e.g., CAC per customer, revenue per customer) and any embedded charts.
-   Update data or formulas as needed for custom analysis (e.g., adding new months or representatives).

### Output

-   Analyze results directly in Excel, including totals, KPI summaries, and visualizations.
-   Export charts or tables as images/PDFs for reports or presentations.

## Dependencies

-   **Software**: Microsoft Excel or compatible spreadsheet software.
-   **Dataset**: `KPI-Project.xlsx` (included in the repository).

## Future Enhancements

-   **Automation**: Implement VBA macros or Power Query to automate data aggregation and KPI calculations.
-   **Visualizations**: Add dynamic charts (e.g., line graphs for revenue trends, bar charts for target achievement) using Excel’s charting tools.
-   **Data Validation**: Introduce checks to ensure data consistency (e.g., non-negative values, valid ranges).
-   **Extended Metrics**: Analyze additional KPIs, such as customer retention rates or product-specific sales.
-   **Integration**: Export data to Python or SQL for advanced analysis or dashboard creation (e.g., using Power BI).

## Conclusions

The **KPISync Analytics** project demonstrates that the 2023 sales operation achieved a total revenue of $9,255,000 and acquired 1,228 new customers, with Q4 2023 slightly underperforming revenue targets (93.76% achievement) but surpassing new customer goals (103% achievement); however, the average revenue per customer ($1,986.77 in Q4 vs. $2,500 target) and elevated customer acquisition costs ($372.11 vs. $333.33 target) indicate opportunities for improving upselling strategies and optimizing acquisition efficiency, providing a robust foundation for future sales performance enhancements.
