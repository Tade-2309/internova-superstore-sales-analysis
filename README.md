# Superstore Sales Analysis

**Excel-based sales analysis completed as part of the Internova Data Analytics Virtual Internship (November 2026).**

**Author:** Samson Bukola Oguntade  
**Tools used in this stage:** Microsoft Excel, PivotTables, charts, KPI cards and slicers  
**Analysis period shown on the dashboard:** 2015–2018

## Project overview

This project examines Superstore sales performance and organises the analysis around business questions that a sales or business team could use to understand revenue, customer segments, product performance, geography and shipping patterns.

The Excel work involved reviewing and preparing the sales records, removing duplicate records, creating date-related fields (Order Year, Ship Year and Order Month), summarising the data with PivotTables, and building an interactive dashboard with KPI cards, charts and slicers.

The internship brief also requested SQL analysis, Python-based cleaning or exploration, a dashboard, at least five insights and recommendations, and a short report. This repository documents the Excel work currently completed. Other stages should be added only when they are actually completed and validated.

## Key dashboard figures

| KPI | Reported result |
|---|---:|
| Total sales | $2,261,537 |
| Average sales | $230.77 |
| Sales records / transactions displayed | 9,800 |
| Dashboard order-year range | 2015–2018 |

*The transaction count is reproduced as displayed on the dashboard. It should not be interpreted as a distinct count of Order IDs unless that measure has been confirmed.*

## Selected findings

### Sales by category

| Category | Sales |
|---|---:|
| Technology | $827,456 |
| Furniture | $728,659 |
| Office Supplies | $705,422 |

Technology is the highest-revenue category in the dashboard, followed by Furniture and Office Supplies.

### Top five states by sales

| State | Sales |
|---|---:|
| California | $446,306 |
| New York | $306,361 |
| Texas | $168,573 |
| Washington | $135,207 |
| Pennsylvania | $116,277 |

California and New York are the two largest state contributors in the displayed results.

### Top five sub-categories by sales

| Sub-category | Sales |
|---|---:|
| Phones | $327,782 |
| Chairs | $322,823 |
| Storage | $219,343 |
| Tables | $202,811 |
| Binders | $200,029 |

### Customer ranking shown on the dashboard

The dashboard labels this visual **Top 5 Customer by Average Sales**.

| Customer | Average sales |
|---|---:|
| Tom Ashbrook | $1,460 |
| Grant Thornton | $1,559 |
| Tamara Chand | $1,588 |
| Sean Miller | $1,670 |
| Mitch Willingham | $1,751 |

These figures are transcribed from the dashboard. The precise aggregation and ranking logic should be checked in the workbook before treating them as customer-level average order values.

### Customer segment contribution

| Segment | Share of sales |
|---|---:|
| Consumer | 50.76% |
| Corporate | 30.44% |
| Home Office | 18.79% |

Percentages may differ slightly from 100% due to rounding.

## Business questions

The analysis was structured around 11 questions:

1. What is the total sales revenue?
2. What is the average sales value?
3. How many transactions were recorded?
4. Which product category generates the highest revenue?
5. How does sales performance change monthly and annually?
6. Which states generate the highest sales?
7. Which customer segment contributes most to revenue?
8. Which product sub-categories generate the highest sales?
9. Who are the top five customers by average sales?
10. Which shipping method is most frequently used?
11. How does sales performance vary across regions?

See [the analysis questions and current evidence](documentation/analysis_questions.md).

## Excel workflow

1. Inspected the source sales data.
2. Removed duplicate records as part of data preparation.
3. Created Order Year, Ship Year and Order Month fields.
4. Built PivotTables to summarise sales across relevant dimensions.
5. Created KPI cards and charts for the dashboard.
6. Added slicers, including Ship Mode, Order Year, Ship Year and Region, to support interactive filtering.

**Important filter note:** PivotTable values can change when slicers are applied. The overall dashboard KPI of $2,261,537 is the reported total; a lower value shown in an individual PivotTable may represent a filtered subset. Always check the active slicer selections before comparing figures.

## Repository structure

- `excel/` — Excel workbook and documentation for the spreadsheet analysis.
- `sql/` — reserved for SQL scripts and query results when completed.
- `python/` — reserved for Python cleaning and exploratory analysis when completed.
- `power-bi/` — reserved for a Power BI report if developed.
- `documentation/` — business questions, findings and methodology.

## Limitations and validation notes

- The findings in this README are transcribed from the dashboard figures supplied for this project.
- Monthly and annual trend values, regional totals and shipping-mode counts have not been transcribed here because their exact values were not provided.
- The dashboard includes slicers. A filtered visual should not be compared with an unfiltered KPI without checking the filter context.
- The dashboard's 9,800 transaction figure is reported as displayed; unique Order ID count has not been independently verified.
- The customer visual's aggregation should be checked against the PivotTable or source formulas before drawing conclusions about average customer spend.
- This repository should not be treated as evidence that the SQL, Python or Power BI stages were completed unless those files and methods are added.

## Internship context

This project was assigned as part of the Internova Data Analytics Virtual Internship. The offer described a 15-day programme from 1 November 2026 and set a Superstore Sales Data Analysis task using Python, SQL, Excel and Power BI.

## Ownership

Copyright © 2026 Samson Bukola Oguntade. All rights reserved.

Unless written permission is granted, no permission is given to reproduce, redistribute, or commercially reuse this project's original documentation or analysis. This notice does not claim ownership of third-party datasets, software, or other materials referenced in the project.
