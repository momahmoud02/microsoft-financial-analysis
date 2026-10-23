# Microsoft Financial Analysis (FY2021 - FY2025)

A five-year financial analysis of Microsoft, delivered twice: a Power BI report for interactive review and a structured Excel workbook for line-by-line work.

## Overview

| Item | Detail |
|---|---|
| Period | FY2021 - FY2025 |
| Tooling | Power BI Desktop, DAX, HTML/CSS measures, Excel |
| Statements | Income statement, balance sheet, cash flow |
| Extra views | Segment analysis, product revenue, estimated expenses, KPI targets |

## Power BI report

The report is a single executive page built around seven HTML content visuals and one slicer. The main matrix, **Detailed Financial Matrix (FY 2021-2025)**, presents the three statements side by side with consistent formatting, while the surrounding cards add context and period labels.

Dynamic HTML measures are used instead of stacked native visuals to keep typography, spacing, and number formatting consistent with the rest of the page.

## Excel workbook

`Microsoft_Financial_Analysis_2021-2025.xlsx` contains:

| Sheet | Purpose |
|---|---|
| `Income Statement` | Revenue, cost, operating expenses, and profit |
| `Balance Sheet` | Assets, liabilities, and equity |
| `Cash Flow` | Operating, investing, and financing cash flows |
| `Segment Analysis` | Performance by business segment |
| `Product Revenue` | Revenue by product line |
| `Calendar` | Fiscal period lookup |
| `Expenses_Estimated` | Estimated expense breakdown |
| `KPI_Targets` | Reference targets used in the analysis |

## Repository contents

```text
microsoft-financial-analysis/
|-- Microsoft_Financial_Analysis.pbix
|-- data/
|   `-- Microsoft_Financial_Analysis_2021-2025.xlsx
`-- README.md
```

## How to open

1. Open `Microsoft_Financial_Analysis.pbix` in Power BI Desktop.
2. Allow custom visuals if prompted; the report uses the HTML Content visual.
3. Use the slicer to move between fiscal years.
4. Open the Excel workbook to review or extend the underlying statements.

## Data notes

- Figures are based on Microsoft's public annual reports for FY2021-FY2025. Microsoft's fiscal year ends on 30 June.
- Some expense and target lines are estimates used for analysis and are labelled as such in the workbook.
- This is a personal analytics project and is not affiliated with or endorsed by Microsoft.

## Author

**Mohamed Mahmoud Taha** - Financial Analyst | Data Analyst

GitHub: [momahmoud02](https://github.com/momahmoud02)
