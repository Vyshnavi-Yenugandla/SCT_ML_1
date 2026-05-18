# House Price Prediction using Linear Regression

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques and the Linear Regression algorithm. The model is trained on housing data and predicts property prices based on important features such as living area, number of bedrooms, and number of bathrooms.

The project demonstrates the complete machine learning workflow including data preprocessing, feature selection, model training, evaluation, and prediction.

---

# Features Used

The following features were used for prediction:

* **GrLivArea** – Above ground living area (square feet)
* **BedroomAbvGr** – Number of bedrooms above ground
* **FullBath** – Number of full bathrooms

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

# Machine Learning Algorithm

## Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values. In this project, it is used to estimate house prices based on housing features.

---

# Project Workflow

```text id="i4g5j2"
Data Collection
      ↓
Data Preprocessing
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
```

---

# Dataset

The dataset contains housing information such as:

* Area of the house
* Number of bedrooms
* Number of bathrooms
* House sale prices

The target variable is:

```text id="d0z3ql"
SalePrice
```

---

# Installation

Install the required libraries using:

```bash id="rdrh9x"
pip install pandas numpy matplotlib scikit-learn
```

---

# How to Run the Project

## Step 1: Open Jupyter Notebook

```bash id="36khg8"
jupyter notebook
```

## Step 2: Run the Notebook

Open the project notebook and run all cells sequentially.

---

# Model Training

The dataset is split into:

* Training Data
* Testing Data

The Linear Regression model is trained using Scikit-learn.

Example:

```python id="wlk76p"
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)
```

---

# Model Evaluation

The model performance is evaluated using:

* Mean Squared Error (MSE)
* R² Score

---

# Output

The trained model predicts house prices based on user input features.

Example:

```text id="x5b2uv"
Predicted House Price: $210000
```

---

# Project Structure

```text id="rmjlwm"
house-price-prediction/
│
├── dataset.csv
├── house_price_prediction.ipynb
├── README.md
└── model.pkl
```

---

# Future Improvements

* Add more housing features
* Use advanced algorithms like Random Forest and XGBoost
* Deploy as a web application
* Improve prediction accuracy
* Add data visualization dashboards

---

# Applications

* Real estate price estimation
* Property investment analysis
* Housing market analysis
* Smart property recommendation systems

---

# Resume Description

Developed a House Price Prediction system using Machine Learning and Linear Regression. Performed data preprocessing, feature selection, model training, and prediction using Python and Scikit-learn.

---

# Conclusion

This project demonstrates how Machine Learning can be used to predict house prices accurately using housing-related features. It provides practical experience in data preprocessing, regression modeling, and predictive analytics using Python.
