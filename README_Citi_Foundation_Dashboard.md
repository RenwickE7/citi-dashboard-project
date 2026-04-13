### Citi Foundation Urban Resilience Project — Power BI Dashboard

**Client:** Undugu Society of Kenya (USK)  
**Funder:** Citi Foundation  
**Tool:** Microsoft Power BI Desktop (Report Format v3.2)  
**Dashboard File:** `Citipolished.pbix`  
**Last Updated:** April 2026

\---

## Overview

This Power BI dashboard was developed for **Undugu Society of Kenya (USK)**, a Nairobi-based NGO working with street-connected children and youth across Nairobi, Kisumu, and Eldoret. The dashboard supports programme reporting for the **Citi Foundation Urban Resilience Project**, translating 16 months of field data into an interactive, stakeholder-ready monitoring tool.

The report enables programme officers, management, and donors to track outputs, outcomes, and financial performance across all project components — from street rescue to youth enterprise — in a single consolidated view.

\---

## Dashboard Structure

The report contains **6 pages**, each dedicated to a distinct programme area:

|Page|Description|
|-|-|
|**Overview**|High-level KPIs, cross-cutting indicators, and city-level performance summary|
|**SYA \& Training**|Street Youth Advocacy and vocational/skills training outcomes|
|**VSLA \& Finance**|Village Savings and Loan Associations — group formation, membership, and savings data|
|**CCRC \& Child Protection**|Child Care and Resource Centre metrics and child protection indicators|
|**Rescue \& Reintegration**|Street rescue operations, family tracing, and reintegration into families/communities|
|**Advocacy**|Policy engagement, community sensitisation, and stakeholder outreach activities|

Navigation between pages is handled via **interactive action buttons** embedded in each page header, enabling a clean, app-like user experience.

\---

## Key Features

### Interactive Navigation

* 36 action buttons provide seamless page-to-page navigation without using the default Power BI tab bar.
* Consistent header layout across all pages for a professional, report-style feel.

### KPI \& Summary Cards

* 10 card visuals surface the most critical project metrics at a glance, including beneficiary counts, households supported, and target achievement rates.

### Data Visualizations

* **Clustered column charts** — compare city-level outputs (Nairobi, Kisumu, Eldoret) across reporting periods.
* **Clustered bar charts** — breakdown of beneficiaries by category, gender, or programme stream.
* **Bar charts** — activity completion and output tracking.
* **Line chart** — trend analysis across the 16-month project timeline.
* **Donut and pie charts** — proportional breakdowns (e.g., gender distribution, reintegration outcomes).
* **KPI visual** — progress-against-target comparison with conditional formatting.
* **Gauge visual** — visual representation of overall target completion percentage.
* **Table visual** — detailed tabular data for drill-down analysis.
* **Slicer** — dynamic filtering by city, reporting period, or programme component.

### Branding \& Theme

* Custom Power BI theme applied via **Power BI Theme Generator**, aligned to Citi Foundation and USK brand guidelines.
* Dual logo placement: **Citi Foundation** and **Undugu Society of Kenya** on all pages.
* Consistent typography, colour palette, and visual styling throughout.

\---

## Technical Highlights

* **DAX Measures** — Custom DAX was written to handle complex aggregation scenarios, including a `Households Supported` measure using `SUMMARIZE` and `MAX` to prevent triple-counting across programme streams.
* **City-level disaggregation** — All key indicators can be filtered and compared across the three project cities.
* **Data reconciliation** — The dashboard was built alongside a source programme report, with figures cross-validated at indicator level to ensure accuracy.
* **Multi-page architecture** — Report is structured by programme component rather than by data table, making it intuitive for non-technical programme staff and donors.

\---

## Data Sources

> \*\*Note:\*\* The underlying data model and source files are not included in this repository for data privacy reasons. The `.pbix` file contains the report layout, DAX measures, and visual configuration only.

Primary data sources used during development:

* Programme activity tracking spreadsheets (Excel)
* VSLA group savings registers
* Beneficiary databases (anonymised)
* 16-month narrative and quantitative programme report

\---

## Skills Demonstrated

* Power BI report design and layout
* DAX formula development (calculated measures, aggregation logic)
* Multi-page interactive dashboard architecture
* Data reconciliation and quality assurance
* NGO programme monitoring and M\&E reporting
* Stakeholder-oriented data visualisation
* Custom theme implementation and branding

\---

## About the Developer

This dashboard was developed by **Renwick**, a data analyst specialising in Power BI, Excel, and data visualisation for the development sector. Based in Kenya, with hands-on experience supporting NGO programme reporting, grant management, and M\&E systems across East Africa.

* **Tools:** Power BI, Excel, DAX, Power Query
* **Sector experience:** Child protection, urban youth resilience, community finance (VSLA)

\---

## Repository Contents

```
├── Citipolished.pbix          # Power BI report file
└── README.md                  # This file
```

\---

*For questions about this project or to discuss data consulting work, feel free to reach out via GitHub or LinkedIn.*

