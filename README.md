# FARS Crash Risk Analysis (EDA + Modeling)

This repository contains a data analysis + modeling pipeline using **U.S. Fatality Analysis Reporting System (FARS)** data enriched with **weather** and **Vehicle Miles Traveled (VMT)** information to study how crash risk varies across **space**, **time**, and **conditions**.

## Contents

- `code/eda.ipynb`  
  Exploratory Data Analysis (EDA) focused on the **2015-2018** period, including plots and interpretation notes.  
  Saves visual outputs under `EDA_visualizations/`.

- `code/main.ipynb`  
  Full final report notebook containing the complete workflow:
  - loading and preprocessing FARS data
  - aggregating crashes at the state/year level
  - weather enrichment (from downloaded daily JSON files)
  - VMT integration
  - predictive modeling + clustering analyses for selected locations (e.g., Dallas and Los Angeles)

## Data Notes

The raw dataset is **not included in the repository** due to file size. But inside the **/data** folder, you can find **data.txt** file containing a link to our dataset on kaggle.
- LINK: https://kaggle.com/datasets/5ec8b60293700ec70dbba506d81405e5072dc8fdfbde5718f83f76d37c37aae4

Just download all the files and put them in the **/data** folder.

## How to Run

1. Install dependencies (at minimum):
   - Python 3.x
   - pandas, numpy, matplotlib/seaborn, scikit-learn, statsmodels (and standard Jupyter stack)

2. Run notebooks:
   - Start with `eda.ipynb` for exploratory visuals
   - Run `main.ipynb` for the full preprocessing + modeling pipeline and final report

## Authors

- Luka Zuanović (https://github.com/ZuanovicLuka)
- Patricija Marijanović (https://github.com/patricija-marijanovic)



