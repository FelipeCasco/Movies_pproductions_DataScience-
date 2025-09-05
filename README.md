# Movies_pproductions_DataScience-
Desenvolvimento do estudo em Ciência de Dados denominado estúdio de Hollywood PProductions, com foco em resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos.



imdb-rating-prediction/
│
├── data/
│   ├── raw/                    # Dados brutos
│   │   └── desafio_indicium_imdb.xlsx
│   ├── processed/              # Dados processados
│   │   └── imdb_processed.csv
│   └── external/               # Dados externos
│       ├── budget_data.csv
│       └── awards_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_analysis.ipynb
│   └── 03_model_training.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_processing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── utils.py
│
├── models/
│   ├── best_model.pkl
│   └── model_performance.json
│
├── reports/
│   ├── eda_report.pdf
│   ├── statistical_analysis.pdf
│   └── model_evaluation.pdf
│
├── requirements.txt
├── environment.yml
└── README.md
