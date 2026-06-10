# Housing Price Prediction using Linear Regression

## Overview

This project develops a machine learning model to predict housing prices based on various property characteristics. The workflow includes data preprocessing, feature engineering, exploratory data analysis, model training, and performance evaluation.

The model is built using Linear Regression and demonstrates the complete machine learning pipeline from raw data to prediction.

---

## Problem Statement

Accurate estimation of housing prices is an important task in the real estate industry. This project aims to predict house prices using property-related features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

---

## Dataset

The dataset used for this project was obtained from Kaggle.

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Features include:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room Availability
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

Target Variable:

- Price

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

### Data Preprocessing

- Loaded and inspected the dataset.
- Checked for missing values.
- Removed null records where necessary.
- Converted binary categorical features into numerical values.
- Applied one-hot encoding to furnishing status.

### Feature Engineering

- Applied logarithmic transformation on the area feature to reduce skewness.
- Created a new feature called `facility_score` based on property amenities.

### Exploratory Data Analysis

- Generated a correlation heatmap to understand relationships between variables.
- Visualized the relationship between area and price using scatter plots.

### Model Development

- Split the dataset into training and testing sets.
- Trained a Linear Regression model using Scikit-Learn.
- Generated predictions on unseen test data.

### Model Evaluation

The model was evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess the accuracy and predictive performance of the model.

---

## Visualizations

### Correlation Analysis

A heatmap was generated to identify relationships between housing features and the target variable.

### Area vs Price Analysis

A scatter plot was used to visualize the relationship between property area and house prices.

### Actual vs Predicted Prices

Model predictions were compared with actual house prices to evaluate performance.

---

## Project Structure

```text
housing-price-prediction/
│
├── Housing_Price_Prediction.ipynb
├── requirements.txt
├── README.md
├── Housing.csv
└── images/
    ├── heatmap.png
    ├── area_vs_price.png
    └── actual_vs_predicted.png
```

## Key Learning Outcomes

- Data preprocessing techniques
- Feature engineering
- Handling categorical variables
- Exploratory data analysis
- Linear Regression implementation
- Model evaluation using regression metrics
- Data visualization

---

## Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter tuning
- Cross-validation
- Model deployment using Flask or Streamlit
- Interactive web application for real-time predictions

---

## Author

Vedika Srivastava

## License

This project is intended for educational and learning purposes.
