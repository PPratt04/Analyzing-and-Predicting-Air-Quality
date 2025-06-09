# Analyzing and Predicting Air Quality

This repository contains a data science project focused on analyzing and forecasting air quality trends in various global cities. The project leverages time series modeling techniques, including LSTM neural networks and anomaly detection, to uncover patterns and make predictions based on historical air quality data.

## Overview

Air pollution is a critical environmental issue affecting millions worldwide. This project aims to:
- Analyze historical air quality data from cities like Delhi and London.
- Apply machine learning models to predict future air quality trends.
- Detect anomalies that may indicate unusual pollution events.

## Contents

- `LSTM.ipynb`: Main notebook containing the core analysis and modeling pipeline.
- `Anomaly_Detection.ipynb`: Focused analysis and prediction for Delhi.
- `delhi_air_quality.csv`: Dataset for Delhi.
- `london_air_quality.csv`: Dataset for London.
- `DSAI443 Final Report.docx`: Final written report summarizing the project.
- `environment.yml`: Conda environment file for reproducing the project setup.

## Methods Used

- **Data Preprocessing**: Handling missing values, normalization, and time series formatting.
- **Exploratory Data Analysis (EDA)**: Visualizing trends, seasonality, and pollutant distributions.
- **LSTM Modeling**: Long Short-Term Memory networks for time series forecasting.
- **Anomaly Detection**: Identifying outliers and pollution spikes using statistical and ML-based methods.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/PPratt04/Analyzing-and-Predicting-Air-Quality.git
   cd Analyzing-and-Predicting-Air-Quality
   ```

2. Create the environment:
   ```bash
   conda env create -f environment.yml
   conda activate air-quality
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Results

The models demonstrate promising accuracy in forecasting air quality metrics and successfully flagging anomalous pollution events. Detailed results and visualizations are available in the notebooks and final report.

## Author

**Parker Pratt**  
For questions or collaboration, feel free to reach out via GitHub, Handshake, LinkedIn, or email.
