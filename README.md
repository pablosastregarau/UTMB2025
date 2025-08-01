# UTMB2025 - Ultra Trail running race prediction

This project aims to predict the results of the UTMB 2025 (Ultra-Trail du Mont-Blanc), one of the most prestigious trail running races in the world. It leverages historical runner performance data, along with scraping, data cleaning, feature engineering, and machine learning to estimate race outcomes.

## Goals :

Aggregate UTMB results from 2017 to 2024

Build a structured dataset with runner characteristics (gender, country, age, DNF history, past performance, etc.)

Train a predictive model to estimate rankings or finish times for UTMB 2025

Publish a forecast leaderboard ahead of the 2025 edition

## Technologies

Language: Python, (Java?)

Libraries: requests, pandas, scikit-learn, xgboost, matplotlib, seaborn, (BeautifulSoup?)

Scraping: Iterative ID-based extraction from live.utmb.world

Modeling: Regression and ranking models (XGBoost?)

## Structure

utmb-prediction-2025/
│
├── data/                  # Raw and processed data
├── notebooks/             # EDA and modeling notebooks
├── src/                   # Scraping, cleaning, and prediction scripts
│   ├── scraper.py
│   ├── cleaner.py
│   └── predictor.py
├── README.md
└── requirements.txt

## Author
Pablo Sastre-Garau – Trail runner & data science enthusiast

## Project Status
🟢 [Day-28] Active – Forecast release scheduled before UTMB 2025

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
