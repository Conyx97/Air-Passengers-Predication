# Air Passengers Prediction

## Project Overview
Time series regression to predict monthly airline passengers (1949–1960).

## Results
| Model             | R² Score |
|-------------------|----------|
| Linear Regression | 0.9457   |
| Random Forest     | 0.6803   |
| XGBoost           | 0.5406   |

## Key Learnings
- Time-based train/test split (not random)
- Lag features for time series (Lag_1, Lag_12)
- Linear Regression outperforms trees on data with clear trend + seasonality

## Dataset
Classic Air Passengers dataset — 144 monthly records from 1949 to 1960.