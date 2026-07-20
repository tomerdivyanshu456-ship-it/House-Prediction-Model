

# House Price Prediction Using ML

## Project Overview

This project predicts house prices using Machine Learning regression algorithms. The dataset used is the **Real Estate Valuation Dataset** obtained from Kaggle. The project was implemented in **Google Colab** using Python and Scikit-Learn.

The objective is to compare multiple regression models and identify the best-performing model for predicting house prices based on various property features.

---

## Dataset

**Dataset Name:** Real Estate Valuation Dataset

### Features

* Transaction date
* House age
* Distance to the nearest MRT station
* Number of convenience stores
* Latitude
* Longitude

### Target Variable

* House price of unit area

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib

---

## Machine Learning Models Used

The following regression models were implemented:

### 1. Linear Regression

A simple baseline regression model that establishes a linear relationship between features and house prices.

### 2. Decision Tree Regressor

A tree-based model capable of capturing non-linear relationships in the data.

### 3. Random Forest Regressor

An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

### Step 1: Dataset Upload

The dataset is uploaded directly in Google Colab using:

```python
from google.colab import files
uploaded = files.upload()
```

### Step 2: Data Loading

```python
df = pd.read_csv("Real_Estate.csv")
```

### Step 3: Data Preprocessing

* Converted transaction date into numerical format.
* Selected input features and target variable.
* Split dataset into training and testing sets.

### Step 4: Model Training

The following models were trained:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Step 5: Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Step 6: Visualization

Generated visualizations:

* Model Comparison Plot
* Actual vs Predicted Plot
* Feature Importance Plot


---

## Results Generated

### Model Comparison

A bar chart comparing the R² score of all regression models.

### Actual vs Predicted Values

Scatter plot showing the relationship between actual and predicted house prices.

### Feature Importance

Feature ranking generated from tree-based models.

---

## Saved Files

```text
Result_Images/
│
├── Model_Comparison.png
├── Actual_vs_Predicted.png
└── Feature_Importance.png

model_results.csv
best_house_price_model.pkl
```

---

## Structure

├── Real_Estate.csv
├── House_Price_Prediction.ipynb
├── README.md
├── Model_Comparison.png
├── Actual_vs_Predicted.png

```


## Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost Regressor
* Gradient Boosting Regressor
* Deployment using Flask or Streamlit
* Interactive dashboard for predictions

---

## Conclusion

This project demonstrates the application of Machine Learning regression algorithms for house price prediction. Multiple models were compared, and the best-performing model was selected based on evaluation metrics. The project also includes automated visualization generation and model saving for future use.



## Future Improvements

* Hyperparameter tuning
* Cross-validation
* XGBoost Regressor
* Gradient Boosting Regressor
* Deployment using Flask or Streamlit
* Interactive dashboard for predictions

---

## Conclusion

This project demonstrates the application of Machine Learning regression algorithms for house price prediction. Multiple models were compared, and the best-performing model was selected based on evaluation metrics. The project also includes automated visualization generation and model saving for future use.
