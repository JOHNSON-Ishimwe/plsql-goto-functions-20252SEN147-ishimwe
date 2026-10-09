# PL/SQL GOTO Statements and Functions
**Student:** ishimwe muhire johnson | **ID:** 20252SEN147 | **Course:** INSY 8311
## Overview
THIS REPO contains work of GTO AMD FUNCTIOM ,EXCEPTION HANDLING WITH THE TESTING 
## Repository Structure
plsql-goto-functions-20252SEN147-ishimwe/
│
├── README.md
├── .gitignore
├── 00_setup/
│ └── create_tables.sql
├── 01_goto/
│ ├── A1_number_classifier.sql
│ ├── A2_salary_review.sql
│ ├── A3_illegal_goto.sql
│ └── A4_rewrite_no_goto.sql
├── 02_functions/
│ ├── B1_fn_annual_salary.sql
│ ├── B2_fn_years_of_service.sql
│ ├── B3_fn_calculate_tax.sql
│ ├── B4_fn_dept_name.sql
│ └── C1_fn_validate_payroll.sql
├── 03_tests/
│ ├── B5_functions_in_select.sql
│ ├── test_functions.sql
│ └── test_validate_payroll.sql
├── screenshots/
│ ├── A1_output.png
│ ├── A2_output.png
│ ├── A3_error_and_fix.png
│ ├── A4_output.png
│ ├── B5_select_output.png
│ └── C1_output.png
└── docs/
└── REFLECTION.md

## Summary of Tasks
What GOTO Does

The GOTO statement in PL/SQL performs an unconditional jump from the current point of execution to a target label defined in the code (e.g., <<label_name>>). Execution immediately resumes at the statement following the label, bypassing intermediate statements.
Functions in SQL Expressions

Functions can be invoked directly inside SQL queries because they evaluate to a single value, behaving like built-in database functions (e.g., UPPER(), ROUND()). For a function to be SQL-compatible, it must respect purity rules—specifically, it must not execute DML statements (INSERT, UPDATE, DELETE) unless specifically configured with autonomous transactions.
Handling NO_DATA_FOUND

Queries using SELECT INTO raise NO_DATA_FOUND if zero rows match. Intercepting this exception within an explicit BEGIN...EXCEPTION block allows the subprogram to handle missing data gracefully (e.g., returning NULL or a default fallback value) instead of failing catastrophically.
## Screenshots
![A1](screenshots/A1_output.png) ... (one per screenshot)
## Notes
I used gemni for git folder navigation codes which i did not know at the time .