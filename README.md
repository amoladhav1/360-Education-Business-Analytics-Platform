# 360 Education Business Analytics Platform

> **A Power BI portfolio project focused on transforming business data into interactive, decision-ready insights.**

[![Power BI](https://img.shields.io/badge/Analytics-Power%20BI-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Data-Excel-217346?logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Status](https://img.shields.io/badge/Project-Portfolio%20Project-2563EB)]()

## Overview

The **360 Education Business Analytics Platform** repository contains Power BI project assets, supporting documentation, and data-preparation materials. The goal of a 360° analytics solution is to bring related business information into a unified reporting experience, making it easier to explore performance, identify trends, and support evidence-based decisions.

**Repository note:** The current files include a Power BI report named `Final_Project1.pbix`, the `UrbanNest_RealEstate.xlsx` dataset, and documentation titled *Real Estate 360*. These assets indicate that the currently committed implementation is real-estate-focused. If this repository is intended to showcase education-institute analytics, consider adding the education dataset/report and updating the asset names so the repository title and contents tell a consistent story.

## Project Assets

| File | Purpose |
|---|---|
| [`Final_Project1.pbix`](./Final_Project1.pbix) | Power BI report file |
| [`UrbanNest_RealEstate.xlsx`](./UrbanNest_RealEstate.xlsx) | Excel dataset used for real-estate analysis |
| [`Data Transformation.pdf`](./Data%20Transformation.pdf) | Data preparation / transformation documentation |
| [`Real Estate 360.pdf`](./Real%20Estate%20360.pdf) | Project overview or dashboard documentation |
| [`Property Measures.docx`](./Property%20Measures.docx) | Supporting measure documentation |
| [`Dashboard 1 and 2.docx`](./Dashboard%201%20and%202.docx) | Dashboard notes for pages 1 and 2 |
| [`Dashboard 3.docx`](./Dashboard%203.docx) | Dashboard notes for page 3 |
| [`Dashboard 5 and 6.docx`](./Dashboard%205%20and%206.docx) | Dashboard notes for pages 5 and 6 |

## Objectives

- Consolidate data and reporting assets in one project repository.
- Prepare data for analysis using documented transformation steps.
- Build an interactive Power BI report for exploring business performance.
- Define and organize measures used in report visuals.
- Present findings in a format that supports business users and stakeholders.

## Technology Stack

- **Microsoft Power BI** — report development and data visualization
- **Power Query** — data transformation and preparation
- **DAX** — measures and analytical calculations
- **Microsoft Excel** — source data
- **GitHub** — version control and project documentation

> The tools above describe the project workflow suggested by the repository assets. Exact implementations and individual measures should be confirmed in the PBIX file and supporting documents.

## Getting Started

### Prerequisites

- Windows computer with [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- Microsoft Excel or a compatible spreadsheet application
- Access to the files in this repository

### Open the project

1. Clone or download this repository.
2. Open `Final_Project1.pbix` using Power BI Desktop.
3. If Power BI asks you to locate the source file, select `UrbanNest_RealEstate.xlsx` from the downloaded project folder.
4. Review the queries in **Transform data** to understand the data preparation steps.
5. Explore the report pages, filters, slicers, visuals, and DAX measures.
6. If the source file location changes, update the data source path in Power BI and refresh the model.

### Clone with Git

```bash
git clone https://github.com/amoladhav1/360-Education-Business-Analytics-Platform.git
cd 360-Education-Business-Analytics-Platform
```

## Suggested Analysis Workflow

1. **Understand the source** — inspect the workbook structure, columns, data types, and business meaning.
2. **Transform the data** — standardize values, address missing or duplicate records where appropriate, and set correct data types.
3. **Model the data** — define relationships between tables where required and validate filter behavior.
4. **Create measures** — centralize business calculations using clearly named DAX measures.
5. **Build report pages** — choose visuals that answer specific business questions rather than adding charts without a purpose.
6. **Validate results** — compare key totals with the source data and test slicers and cross-filtering.
7. **Communicate insights** — summarize the most important trends, exceptions, and opportunities for action.

## Quality Checklist

- [ ] Data types and column names are consistent.
- [ ] Missing values and duplicate records have been assessed.
- [ ] Relationships and filter directions have been validated.
- [ ] Measures return expected values at different filter levels.
- [ ] Visuals use clear titles, labels, and number formats.
- [ ] Slicers and interactions work as intended.
- [ ] Source totals reconcile with report totals.
- [ ] Screenshots of the report pages are included in the README or a `screenshots/` folder.
- [ ] Data privacy and licensing have been checked before sharing.

## Repository Structure

```text
360-Education-Business-Analytics-Platform/
├── Final_Project1.pbix
├── UrbanNest_RealEstate.xlsx
├── Data Transformation.pdf
├── Real Estate 360.pdf
├── Property Measures.docx
├── Dashboard 1 and 2.docx
├── Dashboard 3.docx
├── Dashboard 5 and 6.docx
└── README.md
```

## Future Enhancements

- Add screenshots or GIFs of each report page.
- Document the data model and important relationships.
- Include a data dictionary describing the source fields.
- Add a DAX measures reference with definitions and business logic.
- Include a concise findings section with verified insights from the report.
- If education analytics is the intended focus, add the relevant admissions, marketing, student, placement, and finance datasets and align the report pages with those business processes.

## Author

**Amol Adhav**

- GitHub: [@amoladhav1](https://github.com/amoladhav1)
- Repository: [360-Education-Business-Analytics-Platform](https://github.com/amoladhav1/360-Education-Business-Analytics-Platform)

## License

No license file is currently listed in the repository. Unless a license is added, assume that the project is shared for viewing purposes only and that reuse or redistribution is not automatically permitted.
