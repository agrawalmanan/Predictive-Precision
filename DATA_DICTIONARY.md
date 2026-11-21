# Data dictionary

All rows are synthetic. Monetary fields are in unspecified currency units; they are internally consistent simulated values, not real customer records.

| Field | Type | Description |
|---|---|---|
| customer_id | string | Unique competition record identifier |
| customer_age | integer | Customer age in years |
| annual_income | integer | Simulated annual income |
| employment_years | integer | Years in employment |
| dependents | integer | Number of dependents |
| education_level | category | Education category |
| marital_status | category | Marital-status category |
| account_tenure_months | integer | Account age in months |
| credit_limit | integer | Assigned credit limit |
| utilization_ratio | float | Credit utilization ratio |
| avg_monthly_bill_6m | float | Average monthly bill over six months |
| avg_monthly_payment_6m | float | Average monthly payment over six months |
| payment_to_bill_ratio | float | Average payment divided by average bill |
| late_payment_count_6m | integer | Count of late payments in six months |
| max_days_past_due_6m | integer | Maximum days past due in six months |
| cash_advance_ratio | float | Simulated cash-advance activity ratio |
| revolving_balance_ratio | float | Simulated revolving-balance ratio |
| transactions_count_6m | integer | Transaction count over six months |
| payment_status_m1 ... payment_status_m6 | integer | Monthly repayment status: 0=current, 1=1–30 days late, 2=31–60 days late, 3=more than 60 days late |
| default_next_month | integer | Target: 1=default, 0=no default; present only in labelled files |

There are 23 explanatory features, plus the identifier. The target is not a feature.
