# Australian Government Contract Spending & Supplier Analysis

## Project Status

 In development

## Project Overview

This project develops an interactive Power BI dashboard using publicly available Australian Government procurement data.

The dashboard will analyse government contract expenditure across agencies, suppliers and procurement categories. It will also identify supplier concentration, unusually high-value contracts, long contract durations and data-quality exceptions that may require further review.

## Business Objective

The objective is to help procurement and reporting stakeholders understand:

- Where government contract spending is concentrated
- Which agencies manage the highest contract values
- Which suppliers receive the largest contracts
- What categories of goods and services are being purchased
- Which contracts show unusual values, durations or data-quality issues

## Planned Dashboard Pages

1. Executive Overview
2. Agency Spending Analysis
3. Supplier Analysis
4. Procurement Category Analysis
5. Contract Exceptions and Data Quality
6. Supplier Drill-Through

## Tools

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Git and GitHub

## Data Source

The project will use publicly available Australian Government contract data published through AusTender.

Detailed source information will be documented in:

`source/data-sources.md`

## Repository Structure

```text
dashboard/       Power BI project files
data/            Raw, processed and reference data
documentation/   Business requirements and technical documentation
images/          Dashboard screenshots and model diagrams
power-query/     Power Query transformation documentation
reports/         Final project summary
source/          Dataset and licensing information
