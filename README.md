# Depreciation Methods Analysis in Excel

# Overview
This project analyzes two commonly used depreciation methods in Excel: Straight Line Method (SLM) and Diminishing Balance Method (DBM). The goal is to compare how each method affects annual depreciation expense, book value, and financial decision-making.

# Problem Statement
Businesses need to choose a depreciation method that reflects the usage pattern of an asset and supports accurate financial reporting. This project compares SLM and DBM for a fixed asset to understand which method is more suitable under different business situations.

# Objectives
- Calculate depreciation using Straight Line Method.
- Calculate depreciation using Diminishing Balance Method.
- Compare yearly depreciation expense under both methods.
- Analyze the effect of each method on book value over time.
- Derive business insights and recommendations for method selection.

# Tools & Functions Used
- Microsoft Excel
- Financial modeling
- Arithmetic formulas
- Comparative analysis
- Tables and visual charts

# Dataset / Inputs
The analysis is based on the following asset assumptions:
- Asset Price: 500,000
- Scrap Value: 50,000
- Useful Life: 10 years

# Methodology
1. Input the asset cost, scrap value, and useful life.
2. Calculate annual depreciation under Straight Line Method.
3. Calculate depreciation rate and yearly depreciation under Diminishing Balance Method.
4. Prepare a year-by-year depreciation schedule.
5. Compare total depreciation, expense timing, and ending book value.
6. Summarize insights and recommendations.

# Depreciation Formulas
## Straight Line Method (SLM)
Annual Depreciation = (Asset Price - Scrap Value) / Useful Life

## Diminishing Balance Method (DBM)
Annual Depreciation = Opening Book Value × Depreciation Rate

# Key Findings
- Both methods depreciate a total of 450,000 over the asset life.
- The final book value under both methods reaches 50,000.
- SLM gives a fixed annual depreciation expense of 45,000.
- DBM records higher depreciation in the early years and lower depreciation in later years.
- DBM better reflects rapid early asset value loss.

# Insights
- SLM is more suitable when asset usage is stable across its life.
- DBM is more suitable when an asset loses value faster in the initial years.
- The depreciation method selected affects profit reporting and tax planning.
- Even when the final value is the same, the expense timing creates different financial impacts.

# Recommendations
- Use Straight Line Method for assets such as buildings or furniture with steady utility.
- Use Diminishing Balance Method for technology, equipment, or vehicles that lose value quickly.
- Clearly disclose the selected depreciation method in financial reports.
- Align accounting systems with the chosen depreciation schedule for consistency and audit readiness.

# Repository Structure
```text
depreciation-methods-analysis-excel/
├── README.md
├── LICENSE
├── .gitignore
├── data/
│   └── depreciation-calculator.xlsx
├── docs/
│   └── depreciation-methods-analysis.pdf
│   ├── depreciation-dashboard-overview.png
│   ├── slm-calculation-sheet.png
│   ├── dbm-calculation-sheet.png
│   └── comparison-chart.png
└── assets/
    └── project-banner.png
````
# Files Included
- `data/depreciation-calculator.xlsx` — Excel workbook with depreciation calculations and schedules.
- `docs/depreciation-methods-analysis.pdf` — Project documentation with explanation, findings, and recommendations.
- `screenshots/` — Visual previews of workbook sheets and charts.

# How to Use
1. Open the Excel workbook from the `data` folder.
2. Review the input section for asset cost, scrap value, and useful life.
3. Examine the SLM and DBM calculations.
4. Compare the yearly depreciation schedules.
5. Read the PDF documentation for interpretation and recommendations.

# Project Outcome
This project demonstrates practical Excel skills in financial modeling, depreciation analysis, method comparison, and business-oriented reporting.

# Future Improvements
- Add an interactive dashboard for depreciation comparison.
- Include more depreciation methods such as Units of Production.
- Add scenario analysis for different useful lives and scrap values.
