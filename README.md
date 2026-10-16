# Bike-Sharing Demand Analysis — Valencia

An academic data analysis project exploring bike-sharing usage in Valencia, focusing on usage patterns, weather-related factors, and demand prediction.

## Project Goals

- Explore bike-sharing usage patterns.
- Compare usage between La Seu and Beniferri.
- Investigate hourly and weekend trends.
- Explore the relationship between weather conditions and bike usage.
- Build and evaluate linear regression models.

## Project Workflow

1. **Exploratory Data Analysis:** Explore the dataset and identify initial patterns.
2. **Data Visualization:** Visualize usage patterns and compare locations.
3. **References:** Document the references used in the project.
4. **Data Preprocessing:** Prepare the data and create features such as hour of day and weekend indicators.
5. **Modeling:** Train and evaluate linear regression models.

## Tools and Methods

- Python
- Jupyter Notebook
- Data analysis and visualization
- Feature engineering
- Linear regression
- Model evaluation using MAE and R²

## Repository Contents

- `01-eda.ipynb` — Exploratory data analysis
- `02-visualizacion.ipynb` — Data visualization
- `03_referencias.ipynb` — Project references
- `04_preprocesamiento.ipynb` — Data preprocessing and feature engineering
- `05_modelado.ipynb` — Predictive modeling and evaluation
- `usobarriosmeteo_processed.csv` — Processed dataset

## Modeling Results

The models were evaluated using an 80/20 train-test split.

| Model | Features / Approach | MAE | R² |
|---|---|---:|---:|
| Baseline | Predict the mean | 3.38 | — |
| Model 1 | Hour of day and temperature | 3.23 | 0.10 |
| Model 2 | Adds weekend and precipitation | 3.22 | 0.10 |

The expanded model achieved a slightly lower MAE, but the improvement was small. The R² value indicates that the models explain only a limited share of the variation in bike usage. Further feature engineering and alternative modeling approaches could improve predictive performance.

## How to Explore the Project

1. Open the notebooks in GitHub to review the analysis and visualizations.
2. To run the notebooks locally, install the Python libraries required by the code.
3. Keep `usobarriosmeteo_processed.csv` in the repository's root folder when running the modeling notebook, which reads the file using a semicolon separator.

## About

This project was developed as part of my Data Science & AI studies. It provided practical experience in exploratory data analysis, data visualization, preprocessing, feature engineering, and model evaluation.

This is an academic project developed as part of my Data Science & AI studies.
