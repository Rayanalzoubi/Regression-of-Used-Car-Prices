# Regression of Used Car Prices

## Overview

This project focuses on predicting used car prices using Machine Learning techniques.
The workflow includes data preprocessing, feature engineering, model training, evaluation, and submission generation.

The project was developed using:

* Python
* Pandas & NumPy
* Scikit-learn
* AutoGluon
* CatBoost

---

## Dataset

The dataset contains information about used cars such as:

* Brand
* Model
* Model Year
* Mileage
* Engine Specifications
* Transmission Type
* Fuel Type
* Interior/Exterior Colors
* Price (Target Variable)

---

## Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Cleaning categorical features
* Removing unnecessary columns
* Detecting and handling outliers

### 2. Feature Engineering

Created additional features such as:

* Car Age
* Engine Size
* Cylinder Count
* Turbo Indicator
* Electric/Hybrid Indicators
* Brand-Model Combination
* Mileage per Year

### 3. Model Training

Trained multiple machine learning models using AutoGluon, including:

* CatBoost
* LightGBM
* XGBoost
* Random Forest
* Weighted Ensemble Models

### 4. Evaluation

The model performance was evaluated using:

* RMSE (Root Mean Squared Error)

---

## Technologies Used

```python
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
AutoGluon
CatBoost
```

---

## Project Files

```bash
Regression_of_Used_Car_Prices.ipynb
README.md
submission.csv
```

* `Regression_of_Used_Car_Prices.ipynb` contains the complete workflow:

  * Data preprocessing
  * Feature engineering
  * Model training
  * Validation
  * Submission generation

---

## Results

The project achieved competitive RMSE scores through:

* Advanced feature engineering
* Ensemble learning
* Hyperparameter tuning
* Automated machine learning techniques

---

## How to Run

### Install Dependencies

```bash
pip install -U autogluon.tabular
pip install catboost
```

### Run the Notebook

Open the notebook in:

* Google Colab
* Jupyter Notebook

Then run all cells sequentially.

---

## Repository Structure

```bash
├── Regression_of_Used_Car_Prices.ipynb
├── submission.csv
├── README.md
└── requirements.txt
```

---

## Author

Developed by Rayanalzoubi.
