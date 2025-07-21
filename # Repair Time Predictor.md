# Repair Time Predictor

## Overview
Predict aircraft component repair TAT to support proactive maintenance planning.

## Project Structure
- `data/`: sample data.
- `notebooks/`: EDA + model notebook.
- `scripts/`: training and prediction pipelines.
- `models/`: saved regression model.
- `dashboard/`: Excel dashboard.

## Instructions
1. `pip install -r requirements.txt`
2. `python scripts/train_model.py`
3. `python scripts/predict_tat.py`
4. Review `dashboard/TAT_Dashboard.xlsx`

## Results
Model R²: (score). Dashboard supports vendor/RFP insights.

## License
MIT License
