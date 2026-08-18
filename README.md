# Forecasting Cyber Incidents

A notebook-based machine-learning and deep-learning study of cyber-incident patterns, classification, and short-horizon forecasting.

## Overview

This project explores how cyber-incident data can be organized into predictive signals. The notebook works with a **simulated SCI dataset**, compares multiple classifiers across pre-pandemic and post-pandemic periods, and extends the analysis with ensemble, CNN, and LSTM-based approaches.

## What the notebook covers

- TF–IDF vectorization and label encoding for text-based incident data.
- Train/test splitting and comparison of classical classifiers.
- Pre-pandemic and post-pandemic accuracy comparisons.
- Ensemble and CNN-based classification experiments.
- Normalization and sequence creation for time-series modeling.
- An LSTM model used to forecast the next three steps in the simulated annual incident series.
- Visual comparisons of classifier performance and annual incident counts.

## Notebook

Open the notebook directly in Google Colab:

[Open `Forecasting_cyber_crimes.ipynb` in Colab](https://colab.research.google.com/github/Saivamshi-K/Forecasting-Cyber-Incidents/blob/main/Forecasting_cyber_crimes.ipynb)

## Getting started

The notebook can be opened in Google Colab or run locally with Jupyter. A Python environment with common scientific-computing and machine-learning packages is required, including pandas, NumPy, scikit-learn, TensorFlow, Matplotlib, and Seaborn.

```bash
jupyter notebook Forecasting_cyber_crimes.ipynb
```

Run the cells from top to bottom. Because the notebook uses a simulated dataset, its outputs should be interpreted as an experimental demonstration rather than a validated operational forecasting system.

## Scope and limitations

This repository is intended for learning and exploratory analysis. The simulated data, notebook design, and reported outputs are not a substitute for validated cyber-threat intelligence, production monitoring, or operational security decisions. For a production extension, the next steps would include documenting a real data source, defining a reproducible evaluation protocol, and adding stronger validation and experiment tracking.

## Author

**Sai Vamshi Kampati** — Computer Science student focused on cloud, machine learning, and applied analytics.
