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

- [Python](https://www.python.org/) 3.9+, [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Plotly](https://plotly.com/)
- [Scikit-learn](https://scikit-learn.org/) (Ridge, cross‑validation)
- [Dash](https://dash.plotly.com/), [SQLite](https://www.sqlite.org/), [Jupyter](https://jupyter.org/)

## Project Structure
```
water-marking-equipment-monitoring/
├── data/
│   ├── colors.txt
│   ├── database.xlsx
│   └── main_database.db
├── notebooks/
│   ├── generate_data.ipynb
│   └── dashboard.ipynb
├── README.md
├── LICENSE
└── requirements.txt
```

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Generate data (optional)
jupyter notebook notebooks/generate_data.ipynb

# Run dashboard
jupyter notebook notebooks/dashboard.ipynb
