# Big-Data-Analysis-and-Project-Assignment
# NO2 Modeling — Installation & Run Guide

This repository contains code and data to model **NO₂ (ppb)** using multiple ML algorithms.

## Requirements
- Python 3.9–3.11
- Git and Git LFS

## Setup & Run
```bash
# 1) Get the repository and large files
git clone https://github.com/ArK470/Big-Data-Analysis-and-Project-Assignment.git
cd Big-Data-Analysis-and-Project-Assignment
git lfs install
git lfs pull

# 2) Install dependencies
pip install -U jupyter pandas numpy matplotlib seaborn statsmodels scikit-learn xgboost

# 3) Run the project
jupyter notebook
# Open Big_Data_Analysis_and_Project_a1.ipynb and run all cells.
```

## Notes
- If running locally (not on Colab), ignore/remove any `google.colab` mounting lines in the notebook.
