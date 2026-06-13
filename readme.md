# Steam Turbine Digital Twin

## Overview

This project develops a machine learning-based digital twin for a thermal power plant steam turbine.

The model predicts key performance indicators using operational plant data.

## Targets Predicted

- Gross Load (MW)
- HP Turbine Efficiency (%)
- NPHR (kcal/kWh)
- NTHR (kcal/kWh)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Machine Learning Models

- Random Forest Regressor
- Extra Trees Regressor

## Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Model Training
5. Performance Evaluation
6. Digital Twin Interpretation

## Results

| Target | R² Score |
|----------|----------|
| Gross Load | 0.011 |
| HP Turbine Efficiency | 0.008 |
| NPHR | 18.289 |
| NTHR | 16.794 |

## Future Work

- Real-time sensor integration
- XGBoost implementation
- Predictive maintenance module
- Web dashboard deployment
