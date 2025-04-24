# U.S. Real Estate Market Analysis

This project analyzes over 2 million home listings across the United States to identify undervalued properties using PySpark and machine learning techniques.

## 🏠 Project Goal
Help buyers and real estate professionals spot homes priced below expected value based on home features and location.

## 🔧 Tools & Technologies
- PySpark (Google Colab)
- pandas, matplotlib, seaborn
- Spark MLlib (regression, clustering)
- USA Real Estate Dataset (Kaggle)

## 🔍 Approach
- Cleaned large-scale housing data using Spark DataFrames
- Engineered features (price per square foot, log transformations)
- Built regression models and clustering to find pricing anomalies
- Highlighted undervalued homes using model residuals

## 📈 Outcomes
- Identified homes priced significantly below predicted market value
- Provided a scalable process for price prediction and deal discovery

## 📂 Files Included
- `RealEstate_Analysis.ipynb` – analysis notebook
- `undervalued_homes.csv` – output from final model
- Visualizations and insights from exploratory and predictive phases
