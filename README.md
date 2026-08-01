# Predictive Maintenance System for Industrial Sensors

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## Overview

This project implements a predictive maintenance system for industrial sensors. It analyzes sensor data (5 parameters over time), trains a Ridge regression model, and provides interactive forecasts for individual parameters or overall sensor health. The system includes:

- **Data generation** (synthetic data with anomalies).
- **Data analysis** (correlation, visualisation).
- **Machine learning** (Ridge regression with cross-validation).
- **Interactive dashboard** (built with Dash and Plotly).

## Features

- ✅ Synthetic data generation with realistic parameter ranges.
- ✅ Anomaly injection to simulate equipment faults.
- ✅ Time‑series plots and distribution histograms.
- ✅ Weighted prediction for overall sensor health.
- ✅ Parameter‑specific forecasts (e.g., “Check temperature sensor within 5 days”).
- ✅ Web interface for manual prediction requests.

## Technology Stack

- **Python 3.9+**
- **Data:** Pandas, NumPy
- **Visualisation:** Matplotlib, Plotly
- **Machine Learning:** Scikit-learn (Ridge, cross-validation)
- **Dashboard:** Dash, Dash Core Components, Dash HTML Components
- **Database:** SQLite
- **Notebooks:** Jupyter

## Project Structure
