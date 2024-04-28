
# Power BI FINANCE Project

A brief description of what this project does and who it's for

# FINANCE-Dashboard


## Problem Statement

TechnoEdge's Power BI project overview provides an interactive snapshot of finance data, including sales, profit, and transaction details. Visuals such as bar charts and tables display key metrics by segments, products, and countries, allowing for easy analysis and decision-making.

## Objectives

1) Sales Analysis: Interactive report for sales performance by segment, country, product, and discount band with line charts and filters.

2)  Transaction Analysis: Report for transaction trends by date, quantity, payment method, and channel with line charts and slicers.

3) Profitability Analysis: Report for profitability metrics with bullet charts, comparing actual vs target profit margins.

4) Sales Channel Analysis: Report for sales performance by online/offline channels with stacked area charts and drill-through.

5) Customer Analysis: Report for customer demographics, payment methods, and
purchasing patterns with pie charts and filters.

6) Financial Performance Analysis: Report for financial metrics by month, quarter, and year with line charts, KPIs, and interactive features.


## Steps

### Data Modelling

Creating a relationship between tables in the model view of Power BI using a common column improves the accuracy and reliability of data analysis and visualization.

### Data view

Display all geographical datasets in Power BI along with their corresponding data categories, such as city, country, state, and region.


### DAX Functions

Date Functions
Text Functions
Aggregation Functions
Logical Functions
Aggregate Functions

SUM('Finance Sales Data'[Sales])

CALCULATE(SUM('Table A'[Sales]),DATESMTD('Table C'[Transaction Date]))

CALCULATE(SUM('Table A'[Sales]),DATESINPERIOD('Table C'[Transaction Date],LASTDATE('TableC'[Transaction Date]),-30,DAY))

SUM('Table B'[Quantity])

        
Report Snaps ,

![Capture](https://github.com/Sagarbhar/Power-BI-Finance-Project-DAX-/assets/168229258/b699a8cb-8e19-4f80-9e2e-79f519c0dbf2)
    
