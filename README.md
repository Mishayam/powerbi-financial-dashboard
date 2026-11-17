# Financial Dashboard

I created this Power BI report to bring sales, costs, profit and units sold into one view. I wanted to see the overall figures and then explore them by product, country and time period.

## What is in the report

- KPI cards for company-wide sales, costs, profit and units sold, plus a country count.
- A bar chart comparing units sold by product.
- A line chart comparing sales and costs by year.
- A chart comparing profit by product.
- Donut charts showing product count by year and the totals for sales and profit.
- Slicers for year/month, product and country.

The sales-and-profit donut displays two totals. I do not use it as a profit-margin calculation because profit is already part of sales.

## What I practised

I used measures for the summary cards and worked with fields from the sales data, product, calendar and country tables. I also practised choosing chart types, arranging the report page and adding filters for exploring the figures.

Measures used in the report include `Total Sale Company-Wide`, `Total Cost Company-Wide`, `Total Profit Company-Wide`, `Total Unit Sold Company-Wide` and `Total Countries`.

## Open the report

Download [Think_Financials.pbix](Think_Financials.pbix) and open it in Power BI Desktop. Use the slicers to explore different periods, products and countries.

The PBIX contains the saved report and data model. The original source files are not included, so refreshing the data may require updating the source connection in Power Query.

## About this project

This is part of my Power BI learning portfolio. My focus was on building a financial overview and practising measures and interactive reporting.
