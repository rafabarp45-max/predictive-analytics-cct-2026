# Predictive Analytics — CCT College Dublin (2026)

Final project for the Predictive Data Analytics module, CCT College Dublin,
Diploma in Data Analytics (Summer 2026). The notebook covers four independent
tasks, each using a different dataset and modelling approach:

| Question | Task | Dataset | Models |
|---|---|---|---|
| 1 | Regression | Body Fat Prediction | Ridge Regression, Random Forest Regressor |
| 2 | Classification | Facebook Live Sellers in Thailand | K-Nearest Neighbors, Decision Tree |
| 3 | PCA and Clustering | Dry Bean Dataset | K-Means, Agglomerative Clustering (with and without PCA) |
| 4 | Time Series Forecasting | Appliances Energy Prediction | ARIMA, SARIMA |

Each section follows the same structure: dataset justification, exploratory
data analysis, data cleaning decisions (documented and justified rather than
applied silently), model fitting, evaluation, and a written conclusion.

## Repository structure

```
.
├── predictive_analytics_pda_2026.ipynb   # main notebook (all 4 questions)
├── data/
│   ├── Body_fat.csv
│   ├── Live_20210128.csv
│   ├── Dry_Bean_Dataset.csv
│   └── energydata.csv
├── requirements.txt
└── .gitignore
```

## Running the notebook

```bash
pip install -r requirements.txt
jupyter notebook predictive_analytics_pda_2026.ipynb
```

The notebook expects the four CSV files to be in a `data/` subdirectory next
to it, as laid out above.

Note: Question 4 (ARIMA/SARIMA) includes a grid search over model orders that
takes several minutes to run. The notebook is provided with outputs already
computed and saved — re-running the full notebook top to bottom is optional
and not required to review the results.

## Datasets

- **Body_fat.csv** — body measurements and body fat percentage. Distributed
  as part of the course module; the exact public origin of this specific
  variant was not confirmed, so no external citation is given.
- **Live_20210128.csv** — Facebook Live Sellers in Thailand (UCI Machine
  Learning Repository).
- **Dry_Bean_Dataset.csv** — Dry Bean Dataset (UCI Machine Learning
  Repository).
- **energydata.csv** — Appliances Energy Prediction dataset (UCI Machine
  Learning Repository).

## AI usage declaration

Claude was used during the development of this project to assist with
writing and reviewing Python code, and with reviewing the explanatory text
in the notebook. All methodological decisions, interpretation of results,
and conclusions are the author's own.

## Author

Rafael da Rosa Barp
[LinkedIn](https://www.linkedin.com/in/rafabarp)

```
git clone https://github.com/rafabarp45-max/predictive-analytics-cct-2026.git
```
