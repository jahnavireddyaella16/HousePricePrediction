# House Price Prediction using Machine Learning

This project predicts house prices using various machine learning models, focusing on the **California Housing Dataset**. It applies advanced preprocessing, regression algorithms, and evaluation metrics to build an accurate predictive system.

## Objective

To develop a machine learning model capable of predicting housing prices based on features such as population, location, number of rooms, etc., and evaluate its performance.

## Dataset

**Source**: California Housing Dataset
**Size**: ~20,000 rows
**Features**:
  - MedInc (Median Income)
  - HouseAge
  - AveRooms
  - AveOccup
  - Latitude
  - Longitude
  - MedHouseVal (Target)

## Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

- Linear Regression
- Decision Tree Regressor
- **Random Forest Regressor** (Best Performance)

## Steps Performed

1. **Data Cleaning** – Removed nulls, handled outliers.
2. **Feature Engineering** – Created new variables and scaled data.
3. **Model Training** – Trained multiple regression models.
4. **Model Evaluation** – Used RMSE and R² score to evaluate.
5. **Best Model** – Random Forest with RMSE: `0.25` and R²: `0.89`.

## Results

- Random Forest performed the best with:
  - RMSE: `0.25`
  - R² Score: `0.89`
- Improved prediction accuracy by **18%** through scaling and proper preprocessing.

## Visualizations

- Correlation heatmap
- Distribution of housing prices
- Feature importance from Random Forest




