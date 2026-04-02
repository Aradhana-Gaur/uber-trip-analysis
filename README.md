# Uber Trip Analysis 🚖

## Overview
Analysis of Uber trip data (Jan-Feb 2015) across 6 NYC bases 
using Machine Learning to forecast daily trip demand.

## Dataset
- Source: NYC TLC FOIL Request
- Records: ~354 daily aggregated records
- Features: dispatching base, date, active vehicles, trips

## Tech Stack
Python | Pandas | Scikit-learn | XGBoost | Matplotlib | Seaborn

## Key Findings
- B02764 (Danach-NY) holds ~55% market share
- Jan 27 blizzard caused ~40% demand drop (anomaly detected via Z-score)
- Valentine's week (Feb 13-15) showed 20-30% demand spike
- XGBoost performed best with lowest MAPE among all models

## Models Used
| Model | MAPE |
|-------|------|
| XGBoost | ~8-9% |
| Random Forest | ~9-10% |
| Gradient Boosting | ~10% |
| Ensemble | ~8.6% |

## Project Structure
uber-trip-analysis/
├── Uber-Jan-Feb-FOIL.csv
├── uber_analysis.ipynb
└── README.md
