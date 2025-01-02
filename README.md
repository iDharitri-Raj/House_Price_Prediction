# Boston House Price Prediction Using XGBoost Regressor

## Project Overview
This project focuses on predicting house prices in Boston using a dataset containing features like crime rate, average number of rooms, and proximity to employment centers. The model is built using the **XGBoost Regressor** and includes data preprocessing, feature scaling, and model evaluation steps.

---

## Key Features
- **Data Preprocessing:** Includes data loading, missing value checking, and statistical analysis.
- **Feature Correlation Analysis:** Visualizes correlations between features to understand the relationships better.
- **Train-Test Split:** The dataset is divided into training and testing sets.
- **Standardization:** The features are standardized to ensure optimal performance of the model.
- **XGBoost Model:** Trains a model using the **XGBoost Regressor** algorithm, known for its high efficiency and performance.
- **Model Evaluation:** Uses R-squared and Mean Absolute Error (MAE) to assess model performance on both training and test data.
- **Visualization:** Compares actual vs predicted prices for better model insight.

---

## Installation
1. Clone the repository or download the project files.
2. Install the necessary Python libraries using the following command:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```

---

## Data
The dataset used in this project is the Boston Housing Dataset, which contains information about the housing market in Boston.

### Features:
- CRIM: Crime rate
- ZN: Residential land zoned for large-scale properties
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable
- NOX: Nitrogen oxide concentration
- RM: Average number of rooms per dwelling
- AGE: Percentage of owner-occupied units built before 1940
- DIS: Weighted distance to employment centers
- RAD: Accessibility to radial highways
- TAX: Property tax rate
- PTRATIO: Pupil-teacher ratio
- B: Proportion of people of African American descent
- LSTAT: Percentage of lower status population
- PRICE: Median value of owner-occupied homes (target variable)

---

## Model Training
XGBoost Regressor is used for training the model on the processed data.

---

## Model Evaluation
The XGBoost Regressor model achieved the following results:

- Training R-squared: 0.999998
- Training Mean Absolute Error (MAE): 0.0091
- Test R-squared: 0.9052
- Test Mean Absolute Error (MAE): 2.0749

---

## Visualizations
- Actual vs Predicted Prices: A scatter plot visualizing the comparison between the actual and predicted prices.

---

## License
This project is licensed under the [**MIT License**](LICENSE) 
