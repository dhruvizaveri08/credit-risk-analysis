# Credit Risk Analysis

## Project Overview

This project analyses a synthetic loan portfolio to explore how borrower characteristics, credit scores and debt-to-income (DTI) ratios relate to loan default risk.

The project demonstrates practical skills in **Python, SQL, Excel and Power BI**, covering data generation, data cleaning, exploratory data analysis, risk segmentation and dashboard development.

## Project Objectives

- Generate and analyse a dataset containing 1,000 synthetic loan records.
- Clean and prepare data for analysis.
- Calculate the overall synthetic default rate.
- Examine default patterns across credit score and DTI categories.
- Use SQL to perform risk segmentation.
- Present key findings through Excel analysis and a Power BI dashboard.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data generation, cleaning and exploratory data analysis |
| Pandas and NumPy | Data manipulation |
| Matplotlib and Seaborn | Data visualisation |
| SQL (DuckDB) | Data querying and risk segmentation |
| Microsoft Excel | Summary analysis, tables and charts |
| Power BI | Dashboard and visual reporting |
| Google Colab | Python and SQL development environment |

## Project Workflow

1. **Data Generation:** Created 1,000 synthetic loan records.
2. **Data Cleaning:** Checked missing values, duplicates and basic data validity.
3. **Exploratory Data Analysis:** Examined default patterns and borrower characteristics.
4. **SQL Analysis:** Analysed default rates across credit score and DTI categories.
5. **Excel Analysis:** Created summary tables, findings and visualisations.
6. **Power BI Dashboard:** Built a dashboard containing key metrics and risk comparisons.

## Key Findings

### Overall Portfolio Summary

| Metric | Result |
|---|---:|
| Total Loan Records | 1,000 |
| Synthetic Defaults | 442 |
| Non-Defaults | 558 |
| Overall Synthetic Default Rate | 44.2% |

### Credit Score Analysis

| Credit Score Band | Records | Defaults | Default Rate |
|---|---:|---:|---:|
| Below 580 | 494 | 340 | 68.83% |
| 580–669 | 166 | 31 | 18.67% |
| 670–739 | 134 | 33 | 24.63% |
| 740 and above | 206 | 38 | 18.45% |

**Observation:** The below-580 credit score category has the highest synthetic default rate at approximately 69%.

### Debt-to-Income Ratio Analysis

| DTI Band | Records | Defaults | Default Rate |
|---|---:|---:|---:|
| Below 20% | 203 | 51 | 25.12% |
| 20%–39% | 299 | 55 | 18.39% |
| 40%–59% | 278 | 163 | 58.63% |
| 60% and above | 220 | 173 | 78.64% |

**Observation:** The 60% and above DTI category has the highest synthetic default rate, at approximately 79%.

## Dashboard

The Power BI dashboard presents:

- Total loan records
- Synthetic defaults
- Non-defaults
- Overall synthetic default rate
- Default rate by credit score category
- Default count by credit score category
- Default rate by DTI category

## Project Structure

The project files are organised in the `notebook` folder of this repository:

- Python and SQL analysis notebook
- Excel analysis workbook
- Power BI dashboard

## Limitations and Disclaimer

**This project uses entirely synthetic data.**

The 1,000 loan records are artificially generated, and default labels were assigned using predefined rules. They do not represent actual borrower behaviour or real financial institution data.

Therefore:

- Findings are illustrative, not empirical evidence.
- Observed patterns may reflect the rules used to generate the dataset.
- Results should not be used for actual lending or credit decisions.

The purpose of this project is to demonstrate data analysis, SQL querying, financial risk segmentation and data visualisation skills.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- SQL querying and aggregation
- Credit risk segmentation
- Excel-based analysis
- Power BI dashboard development
- Analytical interpretation and reporting

---

**Author:** Dhruvi  
**GitHub:** [dhruvizaveri08](https://github.com/dhruvizaveri08)
