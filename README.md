# Sales \& Revenue Performance Analytics | Interactive Excel Dashboard

**Tools: Microsoft Excel · PivotTables · PivotCharts · Slicers · Timeline Filters · GETPIVOTDATA · Structured Table References**

## Project overview

This portfolio project explores sales performance across products, regions, channels, and customer segments using an interactive Microsoft Excel dashboard. The goal is to turn transactional data into accessible performance metrics and business questions that decision-makers can investigate through filtering.

**Dataset disclosure:** This is an educational practice dataset originally supplied in a dashboard-training file named Excel\_PivotTable\_Dashboard\_Practice\_File.xlsx. The records are not represented as verified real-world company sales. The dataset includes dates through December 2026; the dashboard's Latest Date in Dataset reflects the maximum date in the file, not the current reporting date.

## Business questions

* How much revenue was generated, and how many orders and units were sold?
* How does revenue change across months?
* Which regions, product categories, and sales channels contribute most to revenue?
* Which products lead in revenue?
* How do these results change when users filter the data?

## Dataset and KPIs

The dataset contains 2,000 sales transaction records covering January–December 2026.

| KPI | All-data result | Definition |

|---|---:|---|

| Total Revenue | $2,452,084 | Sum of transaction revenue |

| Total Orders | 2,000 | Count of orders; the dataset contains 2,000 unique order IDs |

| Units Sold | 5,552 | Sum of units/quantity |

| Average Order Value | $1,226.04 | Total revenue divided by total orders |

Displayed KPI figures are rounded in the dashboard for readability.

## Dashboard features and technical implementation

* Built PivotTables and PivotCharts to summarize sales performance by month, region, category, channel, and leading products.
* Developed four KPI displays for revenue, orders, units, and average order value.
* Configured interactive slicers and date filtering; tested coordinated filtering of the dashboard.
* Used GETPIVOTDATA to retrieve KPI values from PivotTable results.
* Used MAX with an Excel structured table reference to display the latest transaction date dynamically.
* Designed a consolidated reporting view that allows users to move from high-level KPIs to category and channel breakdowns.

## Findings from the sample data

1. Category concentration: Computers generated approximately $1.35 million, about 54.9% of overall revenue. This is a useful starting point for investigating concentration risk and category-level demand.
2. Channel performance: Online generated approximately $791,537, about 32.3% of total revenue, making it the largest channel in this sample.
3. Customer mix: Returning customers contributed approximately $1.68 million, about 68.6% of revenue. Further analysis could distinguish repeat-purchase frequency from higher spending per order.

These are descriptive observations from a practice dataset, not causal conclusions or forecasts.

## Potential business actions

* Review category concentration and examine whether sales performance depends heavily on Computers.
* Compare channel performance alongside order counts and average order values before deciding where to invest.
* Segment returning and new customers to explore opportunities for retention, acquisition, and basket-size improvements.

## How to explore the dashboard

1. Download Sales\_Revenue\_Analytics\_Portfolio.xlsx from this repository.
2. Open it in Microsoft Excel desktop and enable editing if prompted and the file is trusted.
3. Open the final dashboard worksheet.
4. Use the slicers and date controls to filter the metrics and charts.
5. Inspect the supporting PivotTables and the formula bar to review calculations, including GETPIVOTDATA and the dynamic latest-date formula.
6. Clear filters to restore the full-dataset view.

**Note:** GitHub does not execute Excel slicers or formulas in its file preview. Download the workbook to test interactivity. A dashboard screenshot or short demo video can provide a quick preview.

## Repository contents

* Sales\_Revenue\_Analytics\_Portfolio.xlsx — interactive Excel workbook with the dashboard and supporting analysis.
* dashboard\_preview.png — full dashboard screenshot (add after exporting).
* dashboard\_demo.mp4 — optional brief demonstration of slicer and KPI interaction (add if recorded).
* README.md — project overview, methods, findings, and usage instructions.

## Limitations and Attribution

The underlying records are educational practice data rather than verified operational findings. Therefore, the insights and recommendations demonstrate analytical techniques and should not be interpreted as actual business performance results.

The original dataset, Excel\_PivotTable\_Dashboard\_Practice\_File.xlsx, was provided by Marg Analytics as part of an Excel PivotTable and Dashboard training tutorial.

The interactive dashboard and supporting analysis reflect my hands-on implementation and customization of PivotTables, PivotCharts, dynamic KPI formulas, slicers, and sales performance visualizations.

**Acknowledgment:** Credit is given to Marg Analytics for providing the original instructional resources and practice dataset. Ownership of the source dataset and instructional materials is not claimed.

