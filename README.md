# SpaceX Falcon 9 First Stage Landing Prediction

This repository contains an end-to-end data science project focused on predicting the landing success of SpaceX Falcon 9 first stages. The project covers the full pipeline: data collection (API & web scraping), data wrangling, exploratory data analysis, visualization, feature engineering, model training, evaluation, and reporting.

## Project Structure

```
├── 01_datenerfassung/         # Data collection (API, web scraping, raw CSVs)
│   ├── data_falcon9_part_1.csv
│   ├── data_falcon9_part_1.1.csv
│   ├── jupyter-labs-spacex-data-collection-api.ipynb
│   └── jupyter-labs-webscraping.ipynb
├── 02_data_wrangling/        # Data wrangling and cleaning
│   ├── dataset_part_2.csv
│   └── labs-jupyter-spacex-Data wrangling.ipynb
├── 03_exploratory_Data_analysis/ # EDA and feature analysis
│   ├── dataset_part_3.csv
│   ├── data_visualization.ipynb
│   └── jupyter-labs-eda-sql-coursera_sqllite.ipynb
├── 04_vizualisation/         # Visualization (Dash, plots)
│   ├── Dash_viz_spacex.py
│   ├── lab_jupyter_launch_site_location.ipynb
│   └── spacex_launch_dash.csv
├── 05_model_training/        # Model training and evaluation
│   ├── dataset_part_2.csv
│   ├── dataset_part_3.csv
│   └── SpaceX_Machine Learning Prediction_Part_5.ipynb
├── 06_Reporting/             # Reporting and appendix
│   ├── combined_workspace.ipynb
│   └── Report_struktur.txt
├── data/                     # Data documentation
├── docs/                     # Project documentation
├── notebooks/                # Additional notebooks
├── requirements.txt          # Python dependencies
└── README.md                 # Project overview (this file)
```

## Key Features

- **Data Collection:**
  - API-based and web scraping of SpaceX Falcon 9/Heavy launch records (Wikipedia, SpaceX API)
  - Parsing and cleaning of raw launch data
- **Data Wrangling:**
  - Structured cleaning, feature extraction, and merging of multiple data sources
- **Exploratory Data Analysis:**
  - Visual and statistical analysis of launch features, payloads, sites, and outcomes
- **Visualization:**
  - Interactive Dash app and static plots (matplotlib, seaborn)
- **Modeling:**
  - Multiple classification models: Logistic Regression, SVM, Decision Tree, KNN
  - Hyperparameter tuning with GridSearchCV
  - Evaluation via accuracy, confusion matrices, and comparative bar plots
- **Reporting:**
  - Consolidated appendix notebook for reproducibility and review
  - Structured report outline and presentation materials

## How to Run

1. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```
2. **Open and run the notebooks:**
   - Start with data collection in `01_datenerfassung/`.
   - Proceed through wrangling, EDA, visualization, and modeling folders.
   - For a complete, reproducible run, use `06_Reporting/combined_workspace.ipynb` (contains all key steps, guarded for safe execution).
3. **Screenshots and reporting:**
   - Use outputs from the consolidated notebook for documentation and appendix.

## Data Sources
- [SpaceX API](https://github.com/r-spacex/SpaceX-API)
- [Wikipedia: List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)
- Provided CSVs in the repository

## Authors
- Project by Dario Beil and contributors


