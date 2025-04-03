# Causal-Inference---Credit-Risk
Understanding the causal impact of loan interest rates on default risk is a critical challenge in the banking industry, as it directly influences pricing strategies, risk management, and financial inclusion efforts. Higher interest rates may increase the financial burden on borrowers, potentially leading to higher default rates, but this relationship can be confounded by factors such as income, credit history, and loan purpose. This project aims to perform a causal inference analysis to determine the effect of loan_int_rate on loan_status (0 for non-default, 1 for default) using a credit risk dataset. By isolating the causal effect, the analysis will provide actionable insights for lenders to optimize interest rate policies while minimizing default risk.

Objectives

Quantify the causal effect of loan_int_rate on loan_status, assessing whether and to what extent higher interest rates lead to increased default probability.

Identify and control for confounding variables to ensure an unbiased estimate of the causal effect.

Validate the robustness of the causal estimate using sensitivity analysis.

Dataset Overview

The dataset contains borrower characteristics, loan details, and default history. The key variables are:

``person_age``: Borrower’s age (numerical).

person_income: Annual income in dollars (numerical).

person_home_ownership: Home ownership status (categorical).

person_emp_length: Employment length in years (numerical).

loan_intent: Purpose of the loan (categorical).

loan_grade: Credit grade of the loan (categorical).

loan_amnt: Loan amount in dollars (numerical).

loan_int_rate: Interest rate as a percentage (numerical), the treatment variable.

loan_status: Loan outcome (binary), the outcome variable.

loan_percent_income: Loan amount as a percentage of income (numerical).

cb_person_default_on_file: Historical default status (binary).

cb_person_cred_hist_length: Length of credit history in years (numerical).
