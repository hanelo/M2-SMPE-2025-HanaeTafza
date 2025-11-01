# M2-SMPE-2025-HanaeTafza
# SMPE — Parallel Quicksort (Python)

This repository mirrors the SMPE logic (teacher’s M2R-ParallelQuicksort) using Python/Jupyter.

## Contents
- `quicksort/run_experiments.ipynb` — generates raw CSV in `quicksort/data/`
- `quicksort/analysis.ipynb` — analysis, CI plots, O(n log n) fit; saves `quicksort/figures/quicksort_analysis.png`
- `journal/journal.md` — dated notes
- `requirements.txt` — minimal Python deps

## Reproduce
```bash
pip install -r requirements.txt
cd quicksort
# In Jupyter: run both notebooks (Restart & Run All)
