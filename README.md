# Predictive Maintenance System for Industrial Sensors

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## Overview

This project predicts when industrial sensors might fail. It uses 5 sensor parameters, trains a Ridge regression model, and shows forecasts through a simple Dash dashboard.

What it does:
- Generates synthetic data with anomalies.
- Analyzes correlations and visualizes trends.
- Trains a model to predict failures.
- Provides a web interface for on‑demand forecasts.

## Features

- ✅ Synthetic data with realistic ranges and injected outliers
- ✅ Time‑series plots and histograms
- ✅ Forecasts for individual parameters (1–5)
- ✅ Overall health prediction ("General")
- ✅ Web dashboard with input field and response

## Tech Stack

- Python 3.9+, Pandas, NumPy, Matplotlib, Plotly
- Scikit-learn (Ridge, cross‑validation)
- Dash, SQLite, Jupyter

## Project Structure
├── data/
│ ├── colors.txt
│ ├── database.xlsx
│ └── main_database.db
├── notebooks/
│ ├── generate_data.ipynb
│ └── dashboard.ipynb
├── README.md
├── LICENSE
└── requirements.txt

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Generate data (optional)
jupyter notebook notebooks/generate_data.ipynb

# Run dashboard
jupyter notebook notebooks/dashboard.ipynb
