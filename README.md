# EV Vehicles Data Analysis

## Overview
Data cleaning and exploratory data analysis (EDA) on the 
Electric Vehicle Population Dataset using Python.

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Linear Regression)
- Google Colab

## Data Cleaning Steps
- Handled missing values in Electric Range (replaced 0 with mean)
- Removed duplicate records
- Anonymized VIN numbers using hashing
- Extracted Longitude & Latitude from Vehicle Location column

## Key Insights
- Top 5 EV makes and models by count analyzed
- EV adoption trend growing significantly by model year
- County-wise EV distribution visualized using heatmap
- CAFV incentive eligibility percentage calculated
- Average Electric Range computed across all EVs

## Visualizations
- Bar chart — Top 5 EV Makes
- Line graph — EV Adoption trend by Model Year
- Heatmap — EV Distribution by County (Top 15)

## Dataset
Source: [Electric Vehicle Population Data](https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data)

## How to Run
1. Clone this repo
2. Install requirements:
   `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `ev_vehicles_analysis.ipynb` in Jupyter or Google Colab
