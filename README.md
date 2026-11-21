# Predictive Precision: Credit Risk Challenge

## Challenge
Build a binary classification model to estimate whether a customer will default on their next credit-card payment.

## Files
- `train.csv`: labelled training data.
- `validation.csv`: labelled validation data for model selection and local checks.
- `test.csv`: unlabelled test data. Generate one probability per `customer_id`.
- `submission_template.csv`: required submission format.

## Target
`default_next_month`:
- `0`: no default
- `1`: default

## Submission format
Submit a CSV with exactly these columns:
- `customer_id`
- `default_probability`

`default_probability` must be a numeric probability between 0 and 1, representing the model's estimated probability of class 1. Do not submit only hard class labels.

Every test `customer_id` must appear exactly once. Preserve the IDs and row coverage from `test.csv`.

## Permitted tools
Participants may use any standard classifier and ordinary data-science libraries, including (but not limited to) scikit-learn, XGBoost, LightGBM and CatBoost, subject to availability in their own environment. Google Colab is recommended.

AI coding assistants may be used if disclosed in the methodology note. Do not use external datasets, leaked labels, or another participant's work.

## Required submission
1. `submission.csv`
2. Your complete `.ipynb` notebook (or source code plus clear execution instructions).
3. A short methodology note (maximum 300 words) describing preprocessing, model choice, validation approach and any AI assistance.

## Evaluation
Primary predictive metric: Average Precision (area under the precision-recall curve, commonly called PR-AUC / AP).
The organizers may inspect code and rerun submissions for reproducibility.

## Important
The dataset is synthetic and created specifically for this competition. It represents a simulated financial-risk scenario and is not real customer data. The validation and test sets are fixed competition splits. Do not attempt to identify or reverse-engineer hidden labels.
