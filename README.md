# LogProspector

LogProspector is a Python notebook that uses Qwen Coder to analyze security logs. It assigns each entry a label, a severity score, and a reason.

## Lab 6 results

The tool analyzed 200 SSH log entries and labeled 120 benign, 70 suspicious, and 10 malicious. The results are saved in `triage_results.csv` and `triage_results.json`. The generated Sigma detection rule is saved in `detection_rule.txt`.

## Running the notebook

Open the Lab 6 notebook in JupyterLab, provide your Qwen API key at the hidden prompt, and set `LOG_FILE` to your dataset filename. Run the cells in order. The offline tests check JSON parsing, fallback behavior, and input validation.
