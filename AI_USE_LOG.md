# AI Use Log - DS-Ass4

## AI Tool and task 
Dear Professor Tiji, regarding to use AI tool: I used different GenAIs such as Deepseek, Claude, and chatGPT) for fixing the code erro and optimizing the code structure and 
interpreting the results, but the whole task is not owned by AIs
- Tasks: interpret the assignment requirements; 
	propose a reproducible experimental protocol; 
	scaffold Python/Jupyter code; 
	create result tables/plots and a draft report from the executed experiment; 
	organize the submission files.
- Dataset: UCI Wisconsin Breast Cancer Diagnostic dataset, accessed through the Scikit-learn packaged loader.
	URL: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
## Advice accepted
- Use a fixed stratified holdout and shared stratified folds for all models.
- Include Logistic Regression as a strong simple baseline, two more complex classifiers, and a Dummy reference.
- Use training-only out-of-fold predictions for threshold selection and preserve the holdout for final evaluation.
- Report discrimination, calibration, paired comparisons, intervals, error slices, and capacity/cost sensitivity.
- Keep raw results, environment information, code, and provenance with the notebook.

## Advice rejected or constrained
- Do not choose the winning model or tune a threshold using holdout labels.
- Do not describe benchmark performance as clinical validity or a deployment recommendation.
- The 5:1 false-negative/false-positive cost ratio and 20% alert capacity are illustrative assumptions; 
- No demographic fairness claim is made from feature-based slices.

## Independent verification required from myside 
- Restart the kernel and run all notebook cells from top to bottom in the target environment.
- Verify dataset provenance, target coding, package versions, model settings, output files, and all reported numbers.
- Inspect failed runs/warnings and retain them rather than silently deleting them.
- Check the paired bootstrap and interval interpretation; add any additional statistical method required by the instructor.
- Review every written claim and rewrite the final discussion in the student's own words.
- Record date, environment, any edits, accepted/rejected suggestions, and verification evidence below.
