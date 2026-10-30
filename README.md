# Retail Sales Intelligence

**Google Sheets retail sales analytics dashboard | Portfolio demonstration**

A spreadsheet-based analytical solution for exploring sales performance, revenue, gross profit, product categories, and sales channels. Designed to demonstrate practical business analytics and spreadsheet modeling skills.

> **Live Google Sheets demo:** [Open the spreadsheet](PASTE_YOUR_PUBLIC_GOOGLE_SHEETS_LINK_HERE)  
> Replace the placeholder URL above with the view-only Google Sheets link before publishing this README.

## What the project contains

- **240 fictional sales transactions** covering 2026.
- **30 sample products**, including unit costs, prices, and categories.
- **Sales calculations** for revenue, cost of goods sold (COGS), and gross profit.
- **Channel Summary** comparing Online, Store, and B2B sales.
- **Category Summary** showing product-category performance.
- **Dashboard** with headline metrics and a monthly revenue chart.
- **Guide** with usage notes and assumptions.

## Workbook tabs

| Worksheet | Purpose |
| --- | --- |
| `Products` | SKU catalog, categories, costs and prices |
| `Sales` | Transactions and calculated sales metrics |
| `Channel Summary` | Revenue, profit and order count by sales channel |
| `Category Summary` | Revenue, profit and units by product category |
| `Dashboard` | KPIs and monthly sales chart |
| `Guide` | Instructions, caveats and data assumptions |

## Key metrics

- Order count and units sold
- Total revenue
- Gross profit and gross margin
- Average order value
- Monthly revenue trend

## Spreadsheet skills demonstrated

Data organization, cross-sheet lookups (`VLOOKUP`), formulas, `SUMIF`, aggregation, KPI design, business reporting and data visualization.

## Try the demo

1. Download `02_Retail_Sales_Intelligence.xlsx` from this repository.
2. Upload it to Google Drive and import it into Google Sheets.
3. Open `Dashboard` to inspect the KPIs and monthly chart.
4. Change a sample product price or sales quantity; verify that associated calculations and summaries update.
5. Restore the original sample values after testing.

## Important notes

- All products, transaction values and other data are **synthetic** and intended for demonstration only.
- Gross profit is revenue minus product cost, **not net profit**; operating expenses, taxes, refunds and shipping are not modeled.
- This is a portfolio prototype, not a production-ready retail accounting or inventory system.
- When adding many new rows, review formula ranges and dashboard source ranges.
- The workbook does not include Apps Script or external integrations.

## Project status

Spreadsheet portfolio demonstration, prepared for GitHub and Google Sheets. Functional checks should be repeated after importing or changing the workbook.
