# Pryzm Solutions Data Quality Assessment

This repository contains a data quality assessment of the UCI Online Retail II dataset, prepared for the Pryzm Solutions Data Integration Intern application.

The dataset is treated as a simulated first customer data handover from a B2B company. The goal is to assess whether the data is ready for pricing intelligence and to identify what would block model training.

## Focus of the Assessment

- Data completeness
- Duplicate detection
- Cancellation and return handling
- Invalid quantities and prices
- Product consistency checks
- Outlier checks
- Commercial risk scoring
- Customer intake specification
- Repeatable onboarding runbook

## Business Goal

The assessment focuses on how data quality affects:

- revenue readiness
- cost-to-clean risk
- customer service risk
- pricing model readiness

## Main Recommendation

Build an automated Customer Data Quality Scorecard before onboarding starts.

This would help Pryzm:
- reduce manual data cleaning
- speed up customer onboarding
- improve customer feedback
- protect pricing model quality
- make onboarding more repeatable and scalable

## Files

- `pryzm_data_quality_framework_online_retail_Anita_Skynar.ipynb`  
  Reusable Python/pandas notebook with quality checks and business scorecards.

## Dataset

Dataset source: UCI Machine Learning Repository, Online Retail II  
https://archive.ics.uci.edu/dataset/502/online+retail+ii

The dataset itself is not uploaded to this repository.
