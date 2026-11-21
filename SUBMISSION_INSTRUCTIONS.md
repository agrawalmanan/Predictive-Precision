# Submission instructions

1. Download `test.csv` and `submission_template.csv`.
2. Generate a probability estimate for class `1` (`default_next_month`) for every row in `test.csv`.
3. Save the file as `submission.csv`.
4. Confirm the file has exactly two columns: `customer_id`, `default_probability`.
5. Upload `submission.csv`, your `.ipynb` notebook and methodology note through the official Google Form.
6. Submit before the announced deadline. Late or incomplete submissions may be rejected.

## Validation checklist
- [ ] Exactly 4,500 prediction rows.
- [ ] No duplicate customer IDs.
- [ ] Every test customer ID appears exactly once.
- [ ] No missing probabilities.
- [ ] All probabilities are numeric and within [0, 1].
- [ ] Notebook/source code is included.
- [ ] AI assistance is disclosed, if used.
