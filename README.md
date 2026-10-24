# Global Electronics Sales Analysis

![Global Electronics Sales Analysis dashboard](assets/dashboard-preview.png)

A Power BI dashboard created for DASHWIZ at CELISTA '25, a national-level technical symposium held at Meenakshi Sundararajan Engineering College, Chennai, on 15 April 2025. The certificate records a first-place award.

## What was the project?

The competition involved a Power BI task and an Excel dataset. The aim of this project was to turn the supplied sales data into a dashboard that makes key information easier to explore.

## What does the dashboard show?

- Revenue by product
- Revenue by region
- Units sold by customer segment
- Actual revenue compared with forecast revenue
- Profit trends from 2018 to 2023

## Tools used

- Microsoft Power BI Desktop — to build the dashboard
- Microsoft Excel — to work with the supplied dataset

## Dataset

The workbook contains 3,000 data rows, 13 columns and one worksheet. Its order dates span 2018–2023.

The data includes orders, dates, regions, countries, products, categories, customer segments, units sold, unit prices, revenue, cost, profit and forecast revenue.

See `docs/data-dictionary.md` for the column descriptions.

## Project files

- `dashboard/global-electronics-sales.pbix` — Power BI report
- `data/global-electronics-sales-data.xlsx` — Excel dataset
- `assets/dashboard-preview.png` — dashboard screenshot
- `docs/data-dictionary.md` — dataset field descriptions

## How to open the report

1. Install Microsoft Power BI Desktop.
2. Open `dashboard/global-electronics-sales.pbix`.
3. If asked, reconnect the dataset to `data/global-electronics-sales-data.xlsx`.
4. Refresh the data and check that all visuals display correctly.

## Data checks

Initial checks found no blank cells or duplicate OrderID values in the dataset. The following calculations were also checked:

- UnitsSold × UnitPrice = TotalRevenue
- TotalRevenue − COGS = Profit

These checks do not prove that every visual is correct or that the forecast is accurate.

## Notes

The report screenshot shows a last-saved timestamp of 15 April 2025. The certificate separately records the competition date.

The dataset's currency, original source and forecast method have not been confirmed from the available files. Check the competition's sharing rules before publishing the dataset or report publicly.
