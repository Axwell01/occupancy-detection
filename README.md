# Occupancy Detection in Residential Buildings using Machine Learning

KTH – AI applications in Sustainable Energy Engineering (HT26)
Supervisor: Supriya Mini Soman (smso@kth.se)

## Goal
Predict whether an apartment in the KTH Live-In Lab is occupied (1) or empty (0)
from environmental sensor data (indoor temperature, CO2, relative humidity).

## Project steps
1. Literature review
2. Select the most important variables
3. Data pre-processing (missing data, discrepancies – document every fix)
4. Data resampling (uniform time resolution, find the optimal one)
5. Model training: logistic regression, shallow neural network, deep neural network
6. Hyperparameter tuning for each model
7. Cross-validation, comparison, best model
8. Real-life applications and comparison with literature

## Folder structure
```
docs/lectures/     Course lectures (L2–L7)
docs/project/      Project description
data/raw/          Original sensor data from the Live-In Lab (not committed)
data/processed/    Cleaned and resampled data (not committed)
notebooks/         Jupyter notebooks for exploration
src/               Python code (preprocessing, models, evaluation)
results/figures/   Plots for the report and presentation
report/            Final report
```

## Getting started
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Timeline
| Date | Activity |
|------|----------|
| 1 Oct 2026 | Project progress I |
| 27 Oct 2026 | Project progress II |
| 18 Nov 2026 | Final presentation |
| Week 49 | Report |
