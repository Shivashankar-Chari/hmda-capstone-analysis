hmda-capstone-analysis/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── hmda_2024_raw.csv (or link/instructions)
│   │
│   ├── processed/
│   │   └── hmda_cleaned.csv
│   │
│   └── external/
│       └── metadata_reference.txt
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   ├── 04_model_building.ipynb
│   ├── 05_model_evaluation.ipynb
│   └── 06_explainability_analysis.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   └── explainability.py
│
├── outputs/
│   ├── figures/
│   │   ├── distributions.png
│   │   ├── feature_importance.png
│   │   └── confusion_matrix.png
│   │
│   ├── tables/
│   │   └── model_metrics.csv
│   │
│   └── reports/
│       └── intermediate_results.md
│
├── docs/
│   ├── data_dictionary.md
│   ├── methodology.md
│   └── assumptions.md
│
├── requirements.txt
└── .gitignore
