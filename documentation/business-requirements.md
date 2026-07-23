# Business Requirements

## Project Title

Australian Government Contract Spending & Supplier Analysis

## Project Status

In development

## 1. Project Background

Australian Government agencies purchase goods and services from external suppliers through contracts. These contracts may cover areas such as information technology, professional services, construction, medical equipment, transport, defence equipment and office supplies.

A large volume of government contract information is publicly available through AusTender. However, raw contract records can be difficult to interpret because they contain many agencies, suppliers, procurement categories, contract values and dates.

This project will transform Australian Government contract data into an interactive Power BI dashboard that makes expenditure patterns easier to understand.

## 2. Business Problem

Procurement and reporting stakeholders need a clear way to understand:

* How much contract expenditure has been recorded
* Which government agencies manage the highest contract values
* Which suppliers receive the largest share of contract expenditure
* What categories of goods and services are being purchased
* How contract expenditure changes over time
* Whether agencies rely heavily on a small number of suppliers
* Which contracts have unusually high values or long durations
* Whether important contract information is missing or inconsistent

Raw CSV files do not provide an efficient way to answer these questions.

## 3. Stakeholder

The primary stakeholder for this project is a hypothetical Australian Government procurement leadership and reporting team.

Other potential users include:

* Procurement managers
* Commercial analysts
* Finance and reporting teams
* Contract managers
* Supplier relationship managers
* Government data analysts
* Audit and assurance teams

## 4. Project Objective

The objective is to develop an interactive Power BI dashboard that analyses Australian Government contract expenditure across agencies, suppliers, procurement categories and time periods.

The dashboard will provide executive-level summaries, detailed supplier and agency analysis, and transparent exception indicators that identify records requiring further review.

The project does not attempt to identify fraud, corruption or misconduct. Exception indicators will only highlight unusual contract values, durations, supplier concentration or data-quality issues.

## 5. Key Business Questions

The dashboard will aim to answer the following questions:

1. What is the total reported value of government contracts?
2. How many contracts, agencies and suppliers are included?
3. Which government agencies manage the highest contract values?
4. Which suppliers receive the highest total contract values?
5. What goods and services receive the most expenditure?
6. How has contract expenditure changed over time?
7. Which suppliers work with the largest number of agencies?
8. How dependent is each agency on its largest suppliers?
9. Which procurement categories are growing?
10. Which contracts have unusually high values?
11. Which contracts have unusually long durations?
12. Which records contain missing, duplicate or inconsistent information?

## 6. Planned Dashboard Pages

### Page 1: Executive Overview

Provides a high-level summary of contract expenditure.

Planned information:

* Total contract value
* Number of contracts
* Number of agencies
* Number of suppliers
* Average contract value
* Contract expenditure over time
* Top agencies
* Top suppliers
* Top procurement categories

### Page 2: Agency Spending Analysis

Analyses expenditure by government agency.

Planned information:

* Agency expenditure ranking
* Number of contracts by agency
* Average contract value by agency
* Agency expenditure trends
* Procurement categories by agency
* Leading suppliers for each agency

### Page 3: Supplier Analysis

Analyses suppliers receiving government contracts.

Planned information:

* Supplier expenditure ranking
* Number of contracts by supplier
* Agencies served by each supplier
* Supplier expenditure trends
* Categories supplied
* Supplier share of total expenditure

### Page 4: Procurement Category Analysis

Analyses what types of goods and services are purchased.

Planned information:

* Contract value by category
* Contract count by category
* Average contract value
* Category trends
* Agencies purchasing within each category
* Suppliers operating within each category

### Page 5: Contract Exceptions and Data Quality

Highlights records that may require further review.

Planned indicators:

* High-value contracts
* Long-duration contracts
* Missing supplier names
* Missing or invalid dates
* Duplicate contract identifiers
* Unclassified procurement categories
* Agencies with high supplier concentration

### Page 6: Supplier Drill-Through

Provides detailed information for a selected supplier.

Planned information:

* Total contract value
* Contract count
* Agencies served
* Procurement categories
* Contract timeline
* Individual contract details

## 7. Project Scope

The project will include:

* Publicly available Australian Government contract data
* Contract expenditure analysis
* Agency analysis
* Supplier analysis
* Procurement category analysis
* Time-based analysis
* Supplier concentration analysis
* Contract exception indicators
* Data-quality monitoring
* Power Query transformations
* Star-schema data modelling
* DAX calculations
* Dashboard documentation
* GitHub and LinkedIn presentation materials

## 8. Out of Scope

The project will not:

* Accuse suppliers or government agencies of misconduct
* Attempt to prove fraud or corruption
* Evaluate the quality of goods or services delivered
* Assess whether individual contracts represent good value for money
* Use confidential or personally identifiable information
* Make legal or audit conclusions
* Treat unusual contracts as evidence of wrongdoing

## 9. Planned Tools

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* Git
* GitHub
* Markdown

Python may be used later if additional data profiling or supplier-name analysis is required.

## 10. Planned Power BI Skills

The project is expected to demonstrate:

* Data collection and profiling
* Power Query transformations
* Folder-based file combination
* Data-type correction
* Text cleaning and standardisation
* Fact and dimension table design
* Star-schema modelling
* Date-table creation
* One-to-many relationships
* DAX measures
* Time-intelligence calculations
* Rankings
* Percentage-of-total measures
* Rolling-period calculations
* Supplier concentration analysis
* Conditional formatting
* Drill-through
* Report-page tooltips
* Dynamic titles
* Bookmarks
* Field parameters
* Data-quality reporting

## 11. Success Criteria

The project will be considered successful when:

* The source data is documented and reproducible
* Important fields are cleaned and validated
* The Power BI model follows a clear star schema
* Dashboard totals reconcile with the source data
* All report pages answer defined business questions
* Users can filter by agency, supplier, category and time
* Supplier concentration measures respond correctly to filters
* Exception indicators use transparent and documented rules
* The dashboard is visually consistent and easy to navigate
* Key findings and recommendations are supported by the data
* The project is fully documented on GitHub
* The final project can be explained clearly during an interview

## 12. Expected Deliverables

The final project will contain:

* Power BI dashboard file
* GitHub repository
* Project README
* Business requirements document
* Data-source documentation
* Data dictionary
* Power Query documentation
* Data-model diagram
* DAX measure documentation
* Dashboard screenshots
* Key findings
* Business recommendations
* Project summary PDF
* LinkedIn project description
* LinkedIn announcement post
* Interview explanation

## 13. Current Progress

* [x] Project selected
* [x] Repository structure created
* [x] Initial business problem defined
* [x] Stakeholder identified
* [x] Business questions drafted
* [ ] Official dataset located
* [ ] Dataset downloaded
* [ ] Data dictionary created
* [ ] Data profiling completed
* [ ] Power Query transformations completed
* [ ] Data model completed
* [ ] DAX measures completed
* [ ] Dashboard pages completed
* [ ] Calculations validated
* [ ] Findings documented
* [ ] Recommendations documented
* [ ] GitHub repository finalised
* [ ] LinkedIn materials prepared
