# DS-A4 Submission Package

## Contents
- `https://github.com/amsalu2212/DS-Ass4/blob/main/Ass4.ipynb` — standalone executable notebook with the complete 
 source integrated into sequential code cells.
- `https://drive.google.com/file/d/1-JLLUkZwMgcbhmK9NXafSJgWyk9bmUz8/view` — report with protocol, results, discussion, figures, and platform summary.
— raw metrics, paired predictions, bootstrap intervals, threshold sensitivity, environment record, and figures.
- `AI_USE_LOG.md` — AI tool/task disclosure and independent verification checklist.
- `requirements.txt` — package versions used to prepare this package.

## Reproduction
1. Create and activate a Python environment (Python 3.10+ recommended).
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `notebook /https://github.com/amsalu2212/DS-Ass4/blob/main/Ass4.ipynb`.
4. Run Kernel → Restart & Run All.
5. Compare regenerated CSVs/figures with the included `results/` folder; record differences and failed runs.

## Data provenance
The data are loaded from the Scikit-learn packaged copy of the Wisconsin Breast Cancer Diagnostic dataset. Original UCI source:
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## Important limitations
The report's results are from one executed run in the package-preparation environment. 
	The data are small and curated. 
	The illustrative cost/capacity assumptions are not clinical utilities. 
	No claim of clinical deployment suitability is made.