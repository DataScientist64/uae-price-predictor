# UAE Property Price Predictor

## Problem
Predict residential property prices across the UAE to support 
investment decisions and property valuation.

## Approach
- Exploratory Data Analysis (EDA) on real-world UAE property dataset
- Feature engineering: location, size, property type, amenities
- Outlier detection and removal
- Compared multiple regression models

## Results
| Model             | R²      | MAE           | RMSE           |
|-------------------|---------|---------------|----------------|
| Linear Regression | -13.69  | 889,993 AED   | 11,805,430 AED |
| Random Forest     | 0.80    | 307,955 AED   | 1,378,863 AED  |

Random Forest significantly outperformed Linear Regression, 
demonstrating the importance of model selection on complex, 
non-linear real estate data.

## Tech Stack
Python · Scikit-Learn · Pandas · NumPy · Matplotlib · Seaborn

## How to Run
1. Clone the repo
2. pip install -r requirements.txt
3. Open uae_property_price_predictor.ipynb in Jupyter
