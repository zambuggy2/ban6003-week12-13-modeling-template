# BAN 6003 Weeks 12-13: Linear Regression and Classification Modeling

**BAN 6003: Data Management and Analytics Integration**  
**Weeks 12-13 GitHub Template**

This repository contains the notebooks and output folder for this assignment package. Detailed lab instructions are provided in Canvas/LMS.

## Canvas / LMS Lab Guide

Read the Canvas/LMS lab guide before working in this repository. The LMS page contains the detailed workflow, submission instructions, and any module-specific notes. This README is only a quick repository checklist.

## Required Notebooks

- `notebooks/module12_linear_regression_guided_lab.ipynb`
- `notebooks/module13_classification_guided_lab.ipynb`

## Data and Outputs

- `data/bike_sharing_daily.csv`: daily bike rentals (Module 12 Final Practice).
- `data/bank_marketing.csv`: bank call campaign clients (Module 13 Applied Practice).
- `data/README_data.md`: sources, licenses, and changes for both files.

Both notebooks also build the same flight-level table from `nycflights13` (flights joined with weather and plane age) and use a reproducible sample of 60,000 flights. Completed outputs belong in `outputs` and are not included in the template.

Expected outputs:

- Module 12: `outputs/linear_regression_metrics_module12.csv`
- Module 12: `outputs/bike_demand_metrics_module12.csv`
- Module 12: `outputs/linear_model_timing_comparison_module12.csv`
- Module 13: `outputs/classification_model_comparison_module13.csv`
- Module 13: `outputs/classification_threshold_comparison_module13.csv`
- Module 13 (optional, not graded): `outputs/bank_campaign_comparison_module13.csv`

## Grading

Weeks 12 and 13 share this repository. Week 12 is graded on the Module 12 deadline from the module12 notebook and its three Module 12 output files. Week 13 is graded on the Module 13 deadline from the module13 notebook and its two required Module 13 output files (the Applied Practice and its file are optional).

## How to Work

1. Create your own GitHub repository from this template.
2. You can work in GitHub Codespaces or in local VS Code. On the UTSA campus network Codespaces may not connect; use the local setup there (see the Canvas page on local setup).
3. Install dependencies with `python -m pip install -r requirements.txt` if working locally.
4. Open the notebook for the current week (Module 12 first, then Module 13).
5. Run cells from top to bottom.
6. Complete all `Your Turn`, Final Practice, Offline Assignment, and reflection sections. The Module 13 Applied Practice is optional.
7. Save your notebook and its required outputs, then commit and push before that week's deadline.
8. Submit your GitHub repository link through Canvas.

## Submit

Submit your GitHub repository link through Canvas before the deadline. Your repository should be public. If your GitHub repository is private, invite the instructor account `zzz1990771` or `zzz1990771@gmail.com` before submitting the link.

If you are using GitHub, a typical commit workflow is:

```bash
git add .
git commit -m "Complete Module 12 lab"   # use "Module 13" in Week 13
git push
```
