# Retail Store Sales — Data cleaning for business use

## Problem I solve
Many businesses work with sales data in Excel or CSV files that:
- look “clean” but are not reliable
- contain dates stored as text, wrong data types, hidden nulls
- break when filtering, sorting or reporting
- cannot be used directly in CRM or business reports

The real problem is not volume — it is **data quality and consistency**.

## What I Do
I transform raw or semi-clean datasets into **business-ready data**, meaning:
- easy to use in Excel
- consistent and validated
- safe for reporting and decision-making
- documented and traceable

## Value
Unlike who:
- clean data mechanically
- fill missing values without justification
- modify data without explaining why
- deliver files that look clean but are not trustworthy

**I work with an analyst mindset, not just as an operator.**

### Differentiators:
- **Audit before cleaning**  
  I analyze data quality before making changes.
- **Business-driven decisions**  
  Every cleaning step has a business logic behind it.
- **No invented data**  
  Missing data is documented, not guessed.
- **Explicit validations**  
  I verify internal consistency (e.g. price × quantity = total).
- **Clear documentation**  
  Clients know exactly what was changed and why.
- **Excel-ready delivery**  
  Output is designed for business users, not only for code.


**Dataset**
- Retail sales dataset (CSV)
- Original records: **12,575**
- Final clean records: **11,362**

**What was done**
- Data quality audit (nulls, duplicates, types, cardinality)
- Proper type conversion (dates, integers)
- Financial consistency validation
- Category and text standardization
- Controlled removal of invalid transactions
- Intentional preservation of non-recoverable missing data
- Final export to Excel for business use


## Key decisions
- Monetary values were not imputed.
- Missing values in `Discount Applied` were preserved because they represent unrecorded data.
- Only transactions that could not represent real sales were removed.
- All decisions were documented for transparency and traceability.


## Deliverables
-  Clean Excel dataset (`.xlsx`)
-  Reproducible cleaning notebook
-  Data dictionary
-  README with scope and decisions

## How I Work With Clients
- Fast execution **without sacrificing data integrity**
- Experienced with:
  - Excel
  - CSV
  - sales, CRM, contacts and operational datasets
- Ideal for:
  - freelancers
  - small businesses
  - analysts who need data ready to use, not just scripts

##  Summary
If you need **data that is truly ready for business**, not just visually clean,
this project shows exactly **how I work and what you can expect**.
