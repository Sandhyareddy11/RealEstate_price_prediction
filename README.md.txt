# Bangalore Real Estate Price Prediction 

This project predicts house prices in Bangalore using machine learning techniques. It includes data cleaning, feature engineering, and regression modeling.

---

## Dataset
- Bengaluru_House_Data.csv contains features like location, total sqft, number of bathrooms, BHK, etc.

---

## Features
- Data cleaning: Removing missing values and invalid entries
- Feature engineering: Created price_per_sqft feature
- Dimensionality reduction: Location-wise filtering
- One-hot encoding for categorical features
- Outlier detection and removal
- Model used: *Linear Regression*
- Hyperparameter tuning with *GridSearchCV*
- Accuracy: *~81%*

---

## Libraries Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn

---

## How to Run

1. Clone this repo
2. Open the Jupyter Notebook
3. Run all cells to train and test the model

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
jupyter notebook