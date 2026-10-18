# COMP2350 — Data Science and Analytics

Student exercise repository for **COMP2350, Fall 2026**.

## Repository contents

- `notebooks/`: 15 weekly Jupyter notebooks with guided examples, core exercises, interpretation prompts, and challenges.
- `data/`: small synthetic datasets used only for teaching and practice.
- `project/README.md`: final-project expectations and submission checklist.
- `environment.yml`: reproducible Anaconda environment for the course.
- `requirements.txt`: Python packages used across the course.

This branch contains **student materials only**. It intentionally does not include completed solutions.

## Getting started

Install [Anaconda](https://www.anaconda.com/download), then open **Anaconda Prompt** (or a terminal where `conda` is available) in this repository folder.

```bash
conda env create -f environment.yml
conda activate comp2350
jupyter lab
```

If the environment already exists and `environment.yml` has changed, update it with:

```bash
conda env update -f environment.yml --prune
```

Open the notebook for the current week and run it from top to bottom. Dataset paths are relative to the `notebooks/` folder, so keep the repository structure unchanged.

## Weekly map

| Week | Topic |
|---:|---|
| 1 | Introduction and data reasoning |
| 2 | Python fundamentals |
| 3 | Functions and NumPy |
| 4 | pandas foundations |
| 5 | Grouping, joining, and reshaping |
| 6 | Data cleaning |
| 7 | Preprocessing and feature engineering |
| 8 | Exploratory data analysis |
| 9 | Probability and simulation |
| 10 | Sampling and statistical inference |
| 11 | Linear regression |
| 12 | Predictive analytics |
| 13 | Model evaluation and ethics |
| 14 | Clustering and association rules |
| 15 | Project template |

## Academic integrity

Submit your own work, cite external sources, and follow the instructor's policy on collaboration and generative AI. Do not commit personal, confidential, or production data.

## Data note

All included CSV files are synthetic. They are designed for instruction and must not be treated as evidence about real people, organizations, or health outcomes.
