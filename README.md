

# Real Estate Price Prediction - Bengaluru

This project aims to predict housing prices in Bengaluru using machine learning techniques. It helps potential buyers and real estate professionals estimate property prices based on important features such as location, area, number of bedrooms, and more.

## Project Overview

- *Objective:* Predict accurate house prices using regression models.
- *Tools & Libraries Used:*
  - Python
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn (Linear Regression, Lasso, Decision Tree)

## 📁 Project Files

- house_prices.ipynb – Main Jupyter Notebook containing data cleaning, EDA, model training, and evaluation.
- Bengaluru_House_Data.csv – Dataset containing house details from Bengaluru.
- README.md – Project documentation.

## Steps Followed

1. *Data Cleaning:*
   - Removed duplicates and null values
   - Handled outliers and rare locations
2. *Exploratory Data Analysis (EDA):*
   - Visualized price trends by location, area, BHK, and other features
3. *Feature Engineering:*
   - Created useful features like price per square foot
   - Converted categorical variables
4. *Model Building:*
   - Trained Linear Regression, Lasso, and Decision Tree Regressor models
   - Compared performance using R² Score
5. *Model Evaluation:*
   - Achieved ~81% accuracy on test data

## Key Results

- Linear Regression performed best with 81% accuracy.
- Location and total square footage were the most influential features.

## Future Improvements

- Integrate a Flask web app for user input and price prediction.
- Try advanced models like Random Forest or XGBoost.
- Improve location categorization using clustering.

## Contact

Created by [Sandhya Reddy](https://github.com/Sandhyareddy11)  
Feel free to connect and suggest improvements!
