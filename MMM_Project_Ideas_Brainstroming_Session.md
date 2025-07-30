Following the file structure that I have decided to follow for this project 

MMM_Ecommerce_Project/
├── data/
│   ├── raw/              # Original raw data
│   ├── processed/        # Cleaned CSVs if you choose to export
│   └── external/         # Optional: e.g., holidays or CPI
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_summary_report.ipynb
│
├── models/               # For saving model pickle files
├── reports/              # Plots and visualizations
│   └── figures/
│
├── requirements.txt      # For reproducibility
├── README.md             # Project overview
└── .gitignore
