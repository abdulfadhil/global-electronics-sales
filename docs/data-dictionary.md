# Data Dictionary

**File:** `global-electronics-sales-data.xlsx`
**Worksheet:** `Sheet1`
**Records:** 3,000 data rows
**Columns:** 13
**Date Range:** 3 January 2018 – 27 December 2023

## Column Descriptions

| Column | Description |
|---|---|
| `OrderID` | Unique identifier recorded for each order. |
| `OrderDate` | Date associated with the order. |
| `Region` | Geographical region associated with the sales record. |
| `Country` | Country associated with the sales record. |
| `Product` | Name of the electronic product. |
| `Category` | Product category recorded in the dataset. |
| `CustomerSegment` | Customer segment associated with the order. |
| `UnitsSold` | Number of units sold in the order. |
| `UnitPrice` | Recorded price per unit. |
| `TotalRevenue` | Total revenue recorded for the order. |
| `COGS` | Cost of goods sold recorded for the order. |
| `Profit` | Profit recorded for the order. |
| `ForecastRevenue` | Forecast revenue value provided in the dataset. |

## Dataset Coverage

The dataset contains:

- **Products:** Desktop, Headphones, Laptop, Smartphone, Smartwatch and Tablet.
- **Regions:** Africa, Asia, Europe, North America, Oceania and South America.
- **Customer Segments:** Consumer, Corporate, Home Office and Small Business.

## Data Validation

The following checks were performed:

- Verified that there were no blank cells.
- Checked for duplicate `OrderID` values.
- Verified that `UnitsSold × UnitPrice = TotalRevenue`.
- Verified that `TotalRevenue − COGS = Profit`.

Both numerical relationships were consistent across the dataset, within a tolerance of 0.01.

## Notes

- The workbook contains one worksheet named `Sheet1`.
- Currency units have not been confirmed.
- The method used to calculate `ForecastRevenue` is not documented in the available files.
