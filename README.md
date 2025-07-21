# ✈️ Repair Time Predictor

A machine learning project to forecast aircraft component repair turnaround time (TAT), designed to improve vendor SLA compliance and reduce delays in aviation maintenance.

---

## 📌 Project Objective

This project aims to:
- Predict repair TAT based on historical vendor data.
- Flag SLA breach risks before they occur.
- Provide a dashboard (Excel-based) for real-time monitoring and decision support.

---

## 🧠 Features

- 🛠 Regression model (Random Forest) to predict TAT.
- 📈 Excel dashboard with vendor risk scores and breach alerts.
- 🔁 Automated prediction pipeline using Python.

---

## 📂 Project Structure

```bash
repair-time-predictor/
├── data/                   # Sample input and output CSV files
├── dashboard/              # Excel dashboard with visualizations
├── models/                 # Trained ML model (.pkl)
├── notebooks/              # Jupyter notebook for EDA + training
├── scripts/                # Python scripts for training & prediction
├── requirements.txt        # Dependencies
└── README.md               # Project overview (this file)
