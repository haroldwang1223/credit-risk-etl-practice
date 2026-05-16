# Credit Risk ETL Practice Project

This is a small Python/pandas practice project built to understand how ETL pipelines can support credit risk reporting.

## Project Overview

The project creates synthetic loan-level data with PD, LGD, and EAD fields. It then performs basic data cleaning, including duplicate removal, missing-value checks, and validation of key risk fields.

After cleaning the data, the project calculates expected loss using:

Expected Loss = PD × LGD × EAD

It also applies a simple stress scenario by increasing PD by 20% and recalculating expected loss. Finally, it summarizes base and stressed expected loss by portfolio and exports the result as a CSV.

The dataset is fully synthetic and does not contain any real client, company, or confidential information.

## Files

- `credit_risk_etl_practice.ipynb`: main notebook
- `synthetic_loans.csv`: synthetic input loan-level data
- `portfolio_risk_summary.csv`: portfolio-level output summary

## What I Practiced

- Reading and inspecting data with pandas
- Checking missing values and duplicates
- Creating calculated risk fields
- Applying a simple stress scenario
- Aggregating results by portfolio
- Exporting cleaned summary output
- Documenting a small data workflow

## Key Learning

This project helped me understand how raw loan-level data can be cleaned, transformed, validated, and summarized for credit risk reporting and stress testing workflows.
