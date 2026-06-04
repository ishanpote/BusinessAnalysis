# Enterprise Sales & Financial Intelligence Workspace

## 📌 Project Overview
This repository contains a multi-page, interactive Business Intelligence dashboard designed to deliver clear financial insights to corporate stakeholders. Built from transactional retail workflows, the workspace uses a structured layout strategy that separates high-level executive summaries from deep regional and product-specific operational drill-downs. By utilizing responsive slicing arrays, custom page navigation indicators, and strict data-to-ink layout controls, this system enables business leaders to pinpoint revenue leaks, forecast seasonality spikes, and optimize capital distribution.

The visualization infrastructure is built entirely inside Power BI using a preprocessed data model.

---

## 🏗️ Workspace Layout & Storyboarding

The workspace is split into two interconnected analysis pages to facilitate progressive disclosure of data:

### 1. Page 1: Strategic Executive Executive Overview
* **Focus:** High-level macro metrics for the C-suite to gauge company-wide momentum.
* **KPI Matrix:** Dynamic summary blocks mapping **Total Revenue**, **Net Profit**, **Units Shipped**, and **Aggregate Profit Margin**.
* **Core Narratives:** * A continuous time-series chart mapping historical performance over a 4-year timeline to uncover cyclical holiday surges.
  * A category division visualization isolating the exact share of business capital flowing through major organizational pillars (*Technology*, *Furniture*, *Office Supplies*).

### 2. Page 2: Operational Regional & Product Drill-Down
* **Focus:** Granular intelligence for division leaders and logistics managers.
* **Core Narratives:**
  * A geographic mapping node utilizing diverging conditional color matrices (Crimson indicating operating deficits, Corporate Blue indicating asset health) to identify regional losses.
  * A sub-category margin matrix that highlights underlying inventory structural vulnerabilities (e.g., identifying sub-categories that maintain large revenue profiles but deliver negative net profit due to steep return or discount rates).

---

## 📂 Repository File Structure
```text
├── README.md                      # Analytical insights and visualization manual
├── Executive_Sales_Workspace.pbix # Complete interactive Power BI dashboard workspace file
├── Executive_Summary_Deck.pptx    # Stakeholder slide deck summarizing core findings
└── Screenshots/                   # Directory housing high-resolution dashboard crops
