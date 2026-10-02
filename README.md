# DSCI 552 Homework 3 - Hou Tianbo

Homework 3 solution: Time series classification Part 1 (feature extraction from the AReM
activity-recognition data) + ISLR 3.7.4 (multiple linear regression on the Auto data).

## Contents
- `Hou_Tianbo_HW3.ipynb` — the executed homework notebook.
- `data/AReM/` — the AReM dataset (7 activity folders, 88 instances, 6 time series each).
- `data/Auto.csv` — the ISLR Auto dataset.
- `requirements.txt` — Python dependencies.

## Notes
- The AReM data is loaded with a robust parser because the official files contain some
  quirks: `bending2/dataset4.csv` is space-separated, `cycling/dataset9.csv` and
  `cycling/dataset14.csv` have a trailing comma on the last row, and `sitting/dataset8.csv`
  has 479 rows instead of 480. The loader handles all of these.
- Part 4 of the assignment (Binary/Multiclass classification) is not included because the
  assignment states it will not be submitted with Homework 3.

## Run
```
pip install -r requirements.txt
jupyter notebook Hou_Tianbo_HW3.ipynb   # then Run All
```
