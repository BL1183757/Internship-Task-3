# Internship-Task-3

# House Price Prediction using Linear Regression

This repository contains the implementation of **Simple and Multiple Linear Regression** models to predict house prices using a housing dataset.

## Objective

To build a regression model using `scikit-learn` that:
- Predicts house prices
- Uses preprocessing (handling categorical + numerical features)
- Evaluates performance using MAE, MSE, and R²
- Interprets model coefficients

---

## 🛠Tools & Libraries Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib / Seaborn (optional for visualization)

---

## Dataset

- Dataset Name: `Housing.csv`
- Columns include both **numerical** and **categorical** features.
- Target variable: `price`

---

## Workflow

1. **Data Preprocessing**
   - Removed missing values
   - Identified numerical and categorical features
   - Applied `StandardScaler` to numerical features
   - Applied `OneHotEncoder` to categorical features
   - Used `ColumnTransformer` to combine preprocessing steps

2. **Model Training**
   - Used `LinearRegression` from `sklearn`
   - Wrapped preprocessing and model in a `Pipeline`
   - Split data into training and testing sets

3. **Model Evaluation**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score


---

## Results (Example)

| Metric | Value |
|--------|--------|
| MAE    | ~850,000 |
| MSE    | ~1.5e+12 |
| R²     | ~0.58 |


---

## Concepts Covered

- Linear Regression (Simple & Multiple)
- Feature Scaling
- One-Hot Encoding
- Pipelines & ColumnTransformers
- Evaluation Metrics (MAE, MSE, R²)

---

## Files in This Repo

- `Task-3.ipynb` – Main notebook with code
- `Housing.csv` – Dataset file
- `README.md` – This file

---

## How to Run

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt` (or install manually)
3. Open `Task-3.ipynb` in Jupyter or VS Code
4. Run all cells

