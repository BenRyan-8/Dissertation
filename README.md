# Dissertation
Predicting Aviation Spare Part Demand: A Machine Learning Approach to Repair Prioritisation

## Overview
This project applies machine learning to predict the probability of an aircraft spare part selling within 60 days of being received. Data is scraped, processed and then models are evaluated and the best-performing model is selected. The model is then used to generate a ranked repair priority list, helping maintenance teams decide which parts are worth repairing first.

## Repository Structure
```
├── notebooks/
│   |── 01_data_collection.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_rank_stock_list.ipynb
├── data/
│   ├── raw/
|   |   └── 777 Parts List.xlsx   # the rest is excluded because it's commercially sensitive
│   └── processed/
│       ├── ATA_chapters_all_parts.csv
│       ├── complete_dataset.csv
│       └── ranked_repair_list.csv
├── model/
│   ├── best_catboost_model.cbm
│   ├── median_imputer.pkl
│   └── cat_features.pkl
└── README.md
```
[nbviewer](https://nbviewer.org)
> **Note:** The model training notebook (03_model_training.ipynb) may not render in GitHub so use the nbviewer link to view it in full.
