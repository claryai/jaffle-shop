---
title: Fix indentation in stg_customers.yml
date: 2025-12-31
affected_files:
  - models/staging/stg_customers.yml
---

## What Was Observed
YAML syntax error due to bad indentation in the `stg_customers.yml` schema file. 

## What Was Changed
- Corrected indentation for `data_tests` and ensured proper YAML structure.

## What Was Accomplished
- Syntax error resolved, allowing successful parsing of the DBT project.

## Evidence Cited
- Confirmed absence of syntax errors after running `dbt parse` successfully.
