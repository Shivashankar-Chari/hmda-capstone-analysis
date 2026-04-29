# HMDA Capstone Analysis

This project focuses on developing a context-aware and explainable analytical framework for modeling mortgage lending outcomes using HMDA data.
Note:  notebooks/: includes initial data exploration and understanding notebook (01_data_understanding.ipynb) (ignore formatting, its only data exploration)

## Objectives

- Identify key drivers of lending decisions
- Build predictive models for classification
- Interpret model outputs using explainability techniques
- Analyze variations across demographic groups

## Dataset

HMDA 2024 Dataset:  
https://ffiec.cfpb.gov/data-publication/modified-lar/2024
https://drive.google.com/file/d/1uA3hU9eCAXi-wey4KL1UuO6AmhGw-Iyp/view?usp=sharing


## Project Structure

```text
hmda-capstone-analysis/
│
├── README.md
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_model_building.ipynb
│   ├── 05_model_evaluation.ipynb
│   └── 06_explainability_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   └── explainability.py
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── reports/
├── docs/
│   ├── data_dictionary.md
│   ├── methodology.md
│   └── assumptions.md
├── requirements.txt
└── .gitignore


Project Folders
data/: stores raw, processed, and supporting data files
notebooks/: contains step-by-step analysis notebooks
src/: contains reusable Python scripts for preprocessing, modeling, evaluation, and explainability
outputs/: stores figures, tables, and generated reports
docs/: contains methodology notes, assumptions, and data documentation

