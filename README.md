# Bike-Sharing Demand Analysis — Valencia

## Project Overview

This project explores bike-sharing usage in Valencia through exploratory data analysis, data visualization, data preprocessing and predictive modeling.

The goal is to identify usage patterns and explore how factors such as time, weekends and weather conditions relate to bike-sharing demand.

## Objectives

- Explore bike-sharing demand and identify usage patterns.
- Compare usage patterns between La Seu and Beniferri.
- Analyze hourly and weekend trends.
- Explore the relationship between weather conditions and demand.
- Build and evaluate a linear regression model.

## Project Workflow

1. **Exploratory Data Analysis (EDA):** Explore the dataset and identify relevant patterns.
2. **Data Visualization:** Visualize demand patterns and compare locations.
3. **References:** Document relevant references used in the project.
4. **Data Preprocessing:** Prepare the data and create features such as hour of day and weekend indicators.
5. **Modeling:** Train a linear regression model and evaluate its performance using MAE and R².

## Tools and Technologies

- Python
- Jupyter Notebook
- Data analysis and visualization
- Feature engineering
- Linear regression
- Model evaluation

## Repository Structure

- `01-eda.ipynb` — Exploratory data analysis
- `02-visualizacion.ipynb` — Data visualization
- `03_referencias.ipynb` — Project references
- `04_preprocesamiento.ipynb` — Data preprocessing and feature engineering
- `05_modelado.ipynb` — Predictive modeling and evaluation

## Key Learning Outcomes

This project provided practical experience in exploring data, communicating patterns through visualizations, preparing features for modeling and evaluating a regression model.

## Notes
## Modeling Results

Two linear regression models were evaluated using an 80/20 train-test split.

- **Baseline:** MAE = 3.38, using the mean of bike usage as the prediction.
- **Model 1:** MAE = 3.23 and R² = 0.10, using hour of day and temperature.
- **Model 2:** MAE = 3.22 and R² = 0.10, adding weekend and precipitation features.

The expanded model achieved a slightly lower MAE, but the overall improvement was limited. Both models had limited explanatory power, suggesting that additional features or alternative modeling approaches could be explored.

This is an academic project developed as part of my Data Science & AI studies.
