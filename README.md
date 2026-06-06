# Global Internet Outage Analyzer (Spark ML)

## Overview

The Global Internet Outage Analyzer is a Big Data analytics project designed to collect, process, and analyze worldwide internet outage data. The system uses Apache Spark for large-scale data processing and machine learning techniques to predict outage risk across different countries.

The results are visualized through an interactive dashboard built with Plotly Dash.

## Key Features

- Real-time/global outage data collection
- Large-scale data processing using Apache Spark (PySpark)
- Machine learning-based outage risk prediction
- Random Forest model for classification
- Interactive world map dashboard
- Data visualization with Plotly Dash
- API integration for live data sources

## Tech Stack

- Apache PySpark
- Python
- scikit-learn (Random Forest)
- Plotly Dash
- IODA API (Internet Outage Detection and Analysis)
- Open-Meteo API

## System Workflow

1. Data is collected from IODA and Open-Meteo APIs  
2. Spark processes and cleans large-scale datasets  
3. Features are extracted for ML training  
4. Random Forest model predicts outage risk per country  
5. Results are visualized on an interactive world dashboard  

## Machine Learning Model

- Algorithm: Random Forest Classifier  
- Goal: Predict probability of internet outage risk per region  
- Input Features: Network signals, outage history, environmental factors  

## Dashboard

The dashboard provides:
- World map visualization of outage risk
- Country-wise risk comparison
- Historical outage trends
- Interactive filtering

## Purpose

This project demonstrates skills in:
- Big Data processing (Spark)
- Machine Learning (classification models)
- API integration
- Data visualization
- End-to-end analytics pipeline

## Contributors

-Muhammad Abdullah
-Abdul Sami Abbasi

## Disclaimer

This project is for academic and research purposes only.

## Deadline

Completed as part of academic coursework (May 2026)
