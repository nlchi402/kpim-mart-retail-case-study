# KPIM Mart — End-to-End Retail Business Intelligence Case Study

A portfolio case study demonstrating how a sales-focused retail dataset can be extended into an integrated business intelligence solution covering sales, inventory, supplier cost, accounts receivable, accounts payable, and working capital.

## Live project

- **Interactive Power BI report:** [Open the dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmFmNzU4MjQtNTk4ZS00NzlhLTg2OGQtOGQ0NGMwZDkxMGEwIiwidCI6IjQxYWI0MmE5LTM4MWItNDhjZi04YTg1LTcyMDQ2NDkyMjk3NiIsImMiOjEwfQ%3D%3D)
- **GitHub Pages case study:** https://github.com/nlchi402/kpim-mart-retail-case-study

## Project overview

The project uses KPIM Mart as a fictional retail business scenario. It starts from a sales-focused dataset and extends the scope with synthetic operational and finance data to demonstrate an end-to-end reporting model.

### Key deliverables

- 12 connected source tables
- 145 documented fields across 11 core data-dictionary tables
- 70 documented DAX and analytical measures
- 6 interactive Power BI report pages
- 3 connected business flows: Sales, Inventory, and Working Capital
- Excel prototyping and reconciliation using XLOOKUP, SUMIFS, structured tables, and PivotTables

## Business problem

Retail performance cannot be assessed reliably through sales alone. Management also needs to understand:

- whether revenue growth is profitable;
- how quickly inventory is moving;
- which suppliers and logistics activities drive cost;
- how receivables, payables, and inventory affect working capital;
- whether actual results are tracking against targets.

The solution connects these areas through shared business dimensions and consistent time logic.

## My contribution

### Business and data design

- Translated retail processes into analytical requirements, table structures, business keys, and reporting grains.
- Extended the original scope with synthetic warehouse, supplier, inventory, accounts payable, and accounts receivable data.
- Built an Excel mock-up and reconciliation layer before Power BI development.
- Defined connected business rules for sales, inventory movements, AR, AP, and working capital.

### Power BI implementation

- Cleaned, typed, reshaped, and standardised data in Power Query.
- Designed the analytical data model.
- Developed 70 documented DAX and analytical measures.
- Built six report pages with slicers, bookmarks, navigation, comparison measures, dynamic display units, and As-of-Date analysis.
- Validated Power Query transformations and DAX outputs against the Excel reconciliation baseline.

## Tools and skills

- Microsoft Excel
- Power BI
- Power Query
- DAX
- Data modelling
- KPI reporting
- Synthetic data design
- Data validation and reconciliation
- Business analysis
- Data storytelling

## Reporting system

1. **Yearly Sales Report**: annual revenue, profitability, growth, and target achievement.
2. **Monthly Sales Report**: monthly performance, prior-month comparison, and weekly trends.
3. **Daily Turnover Report**: MTD sales, daily efficiency, and progress against targets.
4. **Inventory Management**: receipts, issues, stock value, DIO, and inventory turnover.
5. **Inventory Cost**: freight, supplier cost, payables, and DPO.
6. **Working Capital Report**: AR, AP, inventory, DSO, DPO, DIO, CCC, and working capital.

## Dashboard previews

### Yearly Sales Report

![Yearly Sales Report](assets/images/yearly-sales-report.png)

### Monthly Sales Report

![Monthly Sales Report](assets/images/monthly-sales-report.png)

### Daily Turnover Report

![Daily Turnover Report](assets/images/daily-turnover-report.png)

### Inventory Management

![Inventory Management](assets/images/inventory-management.png)

### Inventory Cost

![Inventory Cost](assets/images/inventory-cost.png)

### Working Capital Report

![Working Capital Report](assets/images/working-capital-report.png)

## Repository structure

```text
kpim-mart-retail-bi-case-study/
├── index.html
├── README.md
├── GITHUB_SETUP_GUIDE.md
├── .gitignore
└── assets/
    ├── css/
    │   └── styles.css
    └── images/
        ├── yearly-sales-report.png
        ├── monthly-sales-report.png
        ├── daily-turnover-report.png
        ├── inventory-management.png
        ├── inventory-cost.png
        └── working-capital-report.png
```

## Run locally

Download or clone the repository, then open `index.html` in a browser. For the most reliable local preview, run a simple local web server from the repository folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Portfolio disclosure

This case study starts from a sales-focused retail dataset and extends it with self-designed synthetic operational data for warehouses, suppliers, inventory movements, accounts receivable, accounts payable, and working capital. All figures are illustrative, contain no confidential customer information, and do not represent the actual performance of a real business.

## Author

**Chi Linh Nguyen**  
Bachelor of Applied Data Analytics, majoring in Economics
