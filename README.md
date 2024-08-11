# Steel Properties Prediction

## Project Overview
This project aims to predict key mechanical properties of steel (Yield Strength, Tensile Strength, and Elongation) using three different machine learning models: Linear Regression, Random Forest, and XGBoost. The dataset consists of 312 steel samples, each described by 40 features related to chemical composition and processing parameters.

## Dataset
- **Size**: 312 samples
- **Features**: 40 input features
- **Target Variables**: Yield Strength, Tensile Strength, Elongation

## Models
1. **Linear Regression**: A simple linear approach to modeling the relationship between features and target variables.
2. **Random Forest**: An ensemble learning method based on decision trees, capable of capturing non-linear relationships.
3. **XGBoost**: An optimized distributed gradient boosting library, known for its performance and speed.

## Requirements
- Python 3.7+
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

## Installation
```bash
pip install pandas numpy matplotlib scikit-learn xgboost
