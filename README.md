# RAQEEB

Per-drug prediction of chemotherapy dose modification or delay in triple-negative breast cancer (CALGB 40603).

Code for the paper *Per-Drug Prediction of Chemotherapy Dose Modification in Triple-Negative Breast Cancer: An Exploratory Analysis of the CALGB 40603 Trial* (MASTER 2027).

October 6th University, Faculty of Computer Science and Information Systems, Department of Artificial Intelligence. Supervised by Dr. Reeham Hussein Gabr.

## Data

The data are not included. Request access to CALGB 40603 from [Project Data Sphere](https://www.projectdatasphere.org) and place `treated2.csv` and `aeclean.csv` next to the notebook. They are used as distributed, without changes.

## Run

```
pip install -r requirements.txt
jupyter nbconvert --to notebook --execute RAQEEB.ipynb
```

Takes about 45 minutes on 2 CPU cores. Seeds are fixed (42 and 1, 7, 42, 123, 2024), so the results match the paper. `results.json`, `Table_II_fully_nested.csv` and `Table_S1_fully_nested_by_seed.csv` are the outputs of that run.
