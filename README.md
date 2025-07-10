# ARIMA-Driven Predictive Analytics for E-Commerce: Customer Churn Prediction and Grouping

## Overview
In this project, we aimed to address the challenge of customer churn in the e-commerce domain by using predictive analytics. We combined **RFM segmentation** (Recency, Frequency, Monetary) with the **ARIMA** time series model to identify patterns in customer behavior and forecast churn trends.

The goal was to help businesses identify at-risk customers early and improve retention strategies based on data-driven insights.

## Problem Statement
E-commerce platforms often face difficulty in retaining customers due to inconsistent engagement. A lack of early insight into churn behavior leads to missed opportunities for retention. Our solution focuses on segmenting users and forecasting churn to enable targeted marketing and personalized interventions.

## Key Features
- Segmented customers using RFM analysis based on transactional data
- Applied ARIMA for churn forecasting within each segment
- Built a simple Flask dashboard to visualize churn trends
- Evaluated model performance using RMSE and MAE

## Technologies Used
- Python
- Pandas, NumPy
- RFM
- Statsmodels (ARIMA)
- Flask
- Matplotlib, Seaborn
- Jupyter Notebook

## Dataset
We used a time-stamped customer transaction dataset from an e-commerce setting. The dataset includes user IDs, transaction amounts, and dates — which we used for RFM feature extraction and time series modeling.

## Results
- ARIMA captured churn trends effectively in the Seasonal Buyers segment
- RMSE: 0.0267
- MAE: 0.0213
- Enabled early detection of churn risk and segmentation-based targeting

## Setup Instructions
1. Clone the repo:
```bash
git clone https://github.com/Kolli-VenkataRushita/churn-forecasting.git
cd churn-arima
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Flask app:

```bash
cd app
python app.py
```

The dashboard will be available at: `http://127.0.0.1:5000`

## Project Structure

```
churn-arima/
├── app/                # Flask app files
├── data/               # Dataset files
├── notebooks/          # Exploratory and modeling notebooks
├── static/             # Plots/images
├── templates/          # HTML templates for dashboard
├── models/             # Saved ARIMA models
├── requirements.txt
└── README.md
```

## Contributors

* K. Venkata Rushita
* M. Jaya Sri
* M. Saahithi
* N. Renuka Devi
* Guide: Mr. Y. Ramu
