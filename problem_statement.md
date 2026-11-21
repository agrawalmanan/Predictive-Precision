# PREDICTIVE PRECISION
## Credit Risk Challenge
### Predicting Customer Credit Default Using Machine Learning

**Competition duration:** 2 hours  
**Participation:** Individual  
**Environment:** Google Colab recommended  
**Problem type:** Binary classification

### Background
Financial institutions use historical customer and repayment information to estimate credit risk. Your task is to build a model that predicts whether a customer is likely to default on their next payment.

### Objective
Using the labelled training and validation datasets, develop a machine-learning classifier that estimates the probability of default for each customer in the unlabelled test dataset.

### Target variable
`default_next_month`
- `0`: No default
- `1`: Default

### Data files
- `train.csv`: 21,000 labelled records
- `validation.csv`: 4,500 labelled records
- `test.csv`: 4,500 unlabelled records
- `submission_template.csv`: required prediction format

### Submission requirements
Submit:
1. A CSV named `submission.csv` containing `customer_id` and `default_probability`.
2. Your complete notebook (`.ipynb`) or source code with execution instructions.
3. A methodology note of no more than 300 words.

The probability must be numeric and between 0 and 1. Include every test customer ID exactly once. Do not submit only binary predictions.

### Evaluation
The primary predictive metric is Average Precision (AP), also known as area under the precision-recall curve. Higher scores are better. The organizers will also inspect code quality, methodology and reproducibility.

### Rules
- Work independently. Do not collaborate or exchange code, predictions or answers with other participants.
- Any standard classifier and standard data-science libraries are permitted.
- External datasets, leaked labels, or unauthorized pretrained models are prohibited.
- AI coding assistants are permitted, but their use must be disclosed.
- Do not attempt to access hidden test labels or reverse-engineer the evaluation data.
- Submit all required files before the deadline.
- Organizers may rerun submitted code and request clarification about methodology.
- Organizers' decisions on technical verification and disputes are final.

### Dataset note
This is a competition-specific synthetic dataset. It contains simulated financial records and does not represent real customers or real lending decisions.
