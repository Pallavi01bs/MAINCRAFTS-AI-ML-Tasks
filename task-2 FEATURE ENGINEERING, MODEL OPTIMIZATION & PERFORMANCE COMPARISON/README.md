# Feature Engineering, Model Optimization & Performance Comparison

## House Price Prediction using California Housing Dataset

This project demonstrates feature engineering, preprocessing, model optimization, and performance comparison techniques using the California Housing Dataset. Multiple regression algorithms were trained and evaluated to predict house prices accurately.

---

## Project Overview

The project implements a complete machine learning workflow including:

- Data loading
- Data preprocessing
- Feature scaling
- Train-test splitting
- Model training
- Prediction
- Performance evaluation
- Visualization
- Model comparison

The main objective is to compare different regression algorithms and identify the best-performing model for house price prediction.

---

## Dataset Used

The project uses the California Housing Dataset provided by Scikit-learn.

### Features
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

### Target Variable
- House Price

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Models Used

The following regression algorithms were implemented:

1. Linear Regression
2. Ridge Regression
3. Decision Tree Regressor

---

## Preprocessing Techniques

The following preprocessing techniques were applied:

- Feature and target separation
- Feature scaling using StandardScaler
- Train-test splitting

---

## Evaluation Metrics

The models were evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score

---

## Model Performance

| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | 0.745581 | 0.575788 |
| Ridge Regression | 0.745554 | 0.575819 |
| Decision Tree Regressor | 0.724234 | 0.599732 |

The Decision Tree Regressor achieved the best prediction performance among all models.

---

## Output Visualizations

The project includes:
- Actual vs Predicted House Prices graph
- Model Performance Comparison Output

---

## Project Structure

```text
Feature-Engineering-Model-Optimization/
│
├── Feature Engineering_Model Optimization.ipynb
├── README.md
├── report.pdf

# Author

Pallavi B S
