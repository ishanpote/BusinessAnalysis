# Enterprise Sales & Financial Intelligence Dashboard Workspace

## Project Overview
This repository contains a multi-page, interactive business intelligence dashboard designed to deliver actionable insights to corporate stakeholders. Built from transactional retail workflows, the [...]

The dashboard is implemented in Power BI Desktop with a normalized star schema data model.

## Workspace Layout & Storyboarding
The dashboard uses progressive disclosure principles to move from strategic metrics to granular operational fields across two canvas pages.

### Page 1: Strategic Executive Overview
Purpose: provide a fast, high-level summary of company-wide health for C-suite leaders.

- KPI ribbon with Total Revenue, Net Profit, Units Shipped, and Average Profit Margin %.
- Continuous time-series chart covering a 4-year timeline to surface seasonal and holiday patterns.
- Donut chart showing the share of capital flowing through Technology, Office Supplies, and Furniture.

### Page 2: Operational Performance Drill-Down
Purpose: help regional sales managers and logistics directors identify where margin leaks are occurring.

- Horizontal slicer tiles for Central, East, South, and West regions.
- Geographical sales distribution treemap showing market capture by state.
- Sub-category profitability bar chart sorted by net margin descending.
- High-value consumer table for Customer Name, Segment, Sales, and Net Profit.

## Repository File Structure
```text
├── README.md                      # Strategic project overview and usage notes
├── Executive_Sales_Workspace.pbix # Complete interactive Power BI dashboard workspace file
├── Superstore_Sales_Cleaned.csv    # Cleaned source data used for the dashboard model
└── Screenshots/                   # Optional local staging area for screenshots before upload
```

## Dashboard Screenshots
Use GitHub-hosted image URLs here once the screenshots are uploaded to the repository or copied to a public GitHub URL.

### Screenshot 1: Executive Overview
![Executive Overview Screenshot](https://github.com/user-attachments/assets/1893b1a7-4c52-4519-971c-de5750055291)

### Screenshot 2: Operational Drill-Down
![Operational Drill-Down Screenshot](https://github.com/user-attachments/assets/84450c5d-38e5-48bb-916f-30e331763242)
