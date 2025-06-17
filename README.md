# U.S. Real Estate Price Prediction Project

This project applies machine learning and big data techniques to predict U.S. housing prices using over 1 million listings from the 2024 USA Real Estate dataset (https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset). The goal was to estimate home prices based on common features and identify mid-range pricing trends using PySpark.

## 🧠 Project Focus
- Develop regression models to predict log-transformed home prices
- Evaluate model performance on mid-priced vs. luxury homes
- Explore geographic and structural factors influencing housing values

## 📊 Dataset
- 1M+ records with price, bed, bath, house size, lot size, and zip code
- Cleaned to ~680,000 usable listings after handling missing values and outliers

## 🛠 Tools & Technologies
- PySpark (Spark DataFrames, MLlib)
- Google Colab
- Python (pandas, matplotlib)
- Word (report documentation)

## 📈 Models Used
- **Linear Regression:** Baseline model with R² ~0.46
- **Gradient Boosted Trees (GBT):** Improved accuracy with R² ~0.71, RMSE ~$130,000
- Feature engineering included log transforms, zip code indexing, and vector assembly

## 🚩 Key Outcomes
- GBT model predicted mid-range housing prices effectively
- Log-transformed variables improved model accuracy and distribution symmetry
- High cardinality of zip codes presented encoding challenges
- Bedrooms had less influence on price than expected; zip code was most important
- High-end homes were harder to model due to missing luxury-specific features

## 📄 Files Included
- `Housing Prediction Report.docx`: Full technical report and modeling results
- Notebook & data (to be added if available)

## 📌 Future Improvements
- Add neighborhood and school quality data
- Use geospatial features and price segmentation
- Build interactive tools or dashboards for price prediction
