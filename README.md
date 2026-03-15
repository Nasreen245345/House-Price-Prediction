# House Price Prediction using Machine Learning

## Project Overview
This project predicts house prices based on various property features such as living area, number of bedrooms, location, and other housing attributes. The goal is to build a regression model that can estimate the selling price of houses using historical housing data.

The project demonstrates a complete machine learning pipeline including data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## Dataset
The dataset used in this project is the **House Prices Dataset** from Kaggle.

Dataset Link:  
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

The dataset contains multiple features describing different aspects of residential homes.

### Important Features
Some key features used for prediction include:

- **GrLivArea** – Above ground living area (square feet)
- **BedroomAbvGr** – Number of bedrooms
- **LotArea** – Lot size of the property
- **OverallQual** – Overall quality of the house
- **GarageCars** – Garage capacity
- **TotalBsmtSF** – Total basement area
- **SalePrice** – Target variable (house selling price)

---

## Project Workflow

### 1. Data Preprocessing
- Loaded the dataset using Pandas
- Converted categorical features to numeric using **One-Hot Encoding**
- Handled missing values
- Removed extreme outliers using the **IQR method**

### 2. Data Visualization
Several visualizations were created to understand the dataset:

- Correlation Heatmap
- Scatter Plot (Living Area vs Price)
- Boxplots for outlier detection
- Actual vs Predicted price comparison
- Feature Importance graph

### 3. Feature Scaling
Feature scaling was applied using **StandardScaler** to normalize feature values before training the model.

### 4. Model Training
Two regression models were trained:

- **Linear Regression**
- **Gradient Boosting Regressor**

### 5. Model Evaluation
Models were evaluated using:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

Results:

| Model | MAE | RMSE |
|------|------|------|
| Linear Regression | 13497 | 20032 |
| Gradient Boosting | 13509 | 19747 |

Gradient Boosting produced slightly better performance due to lower RMSE.

---

## Visualization of Results
The following visualizations were generated:

- Actual vs Predicted House Prices
- Feature Importance Plot
- Outlier Detection using Boxplots

These plots help understand model performance and the influence of different features on house prices.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Concepts Applied

- Data Cleaning
- Feature Encoding
- Feature Scaling
- Regression Modeling
- Model Evaluation (MAE, RMSE)
- Data Visualization

---

## Conclusion
The machine learning models were able to successfully learn the relationship between housing features and property prices. The results show that the model can predict house prices with an average error of approximately \$13,500.

Features such as **overall quality, living area, and garage capacity** were found to have a strong influence on house prices.

This project demonstrates the practical application of regression models in real estate price prediction.

---

## Future Improvements
Possible improvements for this project include:

- Hyperparameter tuning
- Using advanced models such as **XGBoost**
- Feature engineering for better prediction accuracy
- Cross-validation for more robust evaluation

---

## Author
Nasreen  
Computer Science Student  
Namal University
