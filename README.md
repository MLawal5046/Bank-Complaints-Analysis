![Dashboard Screenshot](Screenshot%202026-08-20%20224857.png)
# Bank-Complaints-Analysis
Interactive Excel dashboard analyzing customer complaints across Nigerian banks (volume, resolution time, fraud trends)
## Table of Contents
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Technologies](#technologies)
- [Approach](#approach)
- [Status](#status)
- [Credits](#credits)

## Business Understanding
This analysis aims to understand how well Nigerian banks are handling customer complaints, identifying which banks and complaint types occur most frequently, and how efficiently each bank resolves them. It also looks at where complaints are concentrated geographically and whether resolution quality varies by bank or region. The goal is to surface actionable insights that can guide both consumers and banks toward better service accountability.

## Data Understanding
A synthetic dataset of 4255,000 complaint records, calibrated to match real category proportions from the Central Bank of Nigeria's (CBN) 2025 Annual Report. Covers 24 Nigerian banks/fintech, 13 product categories, and all 36 states plus FCT, with dates spanning 2023–2026.

## Technologies
Microsoft Excel (Pivot Tables, PivotCharts, Slicers), Excel Formulas (COUNTIF, AVERAGEIFS), SQL (SQL Server Management Studio)

## Setup
Download the `.xlsx` file from this repository and open in Microsoft Excel (2016 or later recommended for full PivotTable and Slicer support). Data is structured as an Excel Table named `nigerian_bank_complaints`.

## Approach
Sourced and cleaned a 4255,000 row dataset, then built KPIs and PivotTable-based analysis across bank, product, state, and resolution time. Designed an interactive dashboard with slicers for filtering, and derived insights and recommendations from the findings.

## Status
Complete

## Credits
Category proportions calibrated to the Central Bank of Nigeria (CBN) 2025 Annual Report on consumer complaints.
