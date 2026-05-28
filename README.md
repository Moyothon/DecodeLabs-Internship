# House Prices Prediction Model

## Overview
This project was completed as part of the Decodelabs Data Science Internship. 
The goal is to analyze and predict house sale prices using the Kaggle House Prices dataset, covering the full data science workflow from data collection to model building.

## About Dataset
- **Source:** [Kaggle House Prices Competition](S)
- **Size:** 1,460 houses, 81 features
- **Target Variable:** SalePrice

## Project Structure
DecodeLabs-Internship/         
```
├── notebooks/
│   ├── Task_1.ipynb
│   ├── Task_2.ipynb
│   ├── Task_3.ipynb
│   ├── Task_4.ipynb
│   └── Task_5.ipynb
├── README.md
```

## Key Findings
- **OverallQual** is the strongest predictor of SalePrice (correlation: 0.79)
- **GrLivArea** is the second strongest predictor (correlation: 0.71)
- Houses in Northridge sell for an average of $335,295 while Meadow Village 
  averages just $98,576
- SalePrice is right-skewed with a median of $163,000

## Models Built
| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | $34,160 | 0.8479 |
| Random Forest | $30,244 | 0.8807 |

The Random Forest model outperformed Linear Regression, explaining 88% of 
the variation in SalePrice with an average prediction error of $30,244.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
2. Place `train.csv` in the project folder
3. Run notebooks in order from Task_1 to Task_5
