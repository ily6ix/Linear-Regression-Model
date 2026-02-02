
# Linear Regression Model – Predicting Customer Spend

A simple and educational machine‑learning project demonstrating how to build a **Linear Regression Model** that predicts **customer spend** based on **time spent in a mobile app**.

This repository is ideal for beginners learning machine learning, Python, and regression modelling concepts.

## 📌 Project Overview

This project demonstrates an end‑to‑end workflow for building a regression model:

*   Load and preprocess data
*   Train a **Linear Regression** model
*   Generate predictions
*   Evaluate performance (R², MSE, RMSE)
*   Visualize results
*   Interpret coefficients

The model answers a simple question:

> **Does time spent in an app influence how much a customer spends?**

## 📂 Repository Structure
Linear-Regression-Model/
│
├── data/
│ └── sample_app_usage.csv
│
├── notebooks/
│ └── 01_simple_linear_regression.ipynb
│
├── src/
│ └── train_model.py
│
├── README.md
└── requirements.txt


> *Note: Some folders may not exist yet. This structure is recommended for future expansion.*

## ⚙️ Tech Stack

*   **Python 3.x**
*   **scikit-learn** – model training
*   **pandas** – data manipulation
*   **numpy** – numeric operations
*   **matplotlib / seaborn** – visualizations
*   **Jupyter Notebook** (optional)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ily6ix/Linear-Regression-Model
cd Linear-Regression-Model

2. (Optional) Create a virtual environment
bash
python -m venv venv
source venv/bin/activate       # macOS / Linux
venv\Scripts\activate          # Windows
3. Install dependencies
bash
pip install -r requirements.txt
4. Run the model script
bash
python src/train_model.py
5. Use the notebook
bash
jupyter notebook notebooks/01_simple_linear_regression.ipynb
📊 Features
Clean and simple regression workflow

Easy‑to‑read script and notebook

Automatic metric calculations

Visualization of:

Regression line

Actual vs. predicted values

Residual distribution

Useful for assignments, ML introductions, and demonstrations

📈 Example Outputs
Model Coefficients
text
Coefficient (β1): 0.87
Intercept (β0): 2.15
Evaluation Metrics
text
R² Score: 0.78
MSE: 12.4
RMSE: 3.52
Visualization Examples
Scatter plot + regression line

Prediction vs actual comparison

Residual histogram

🔧 Future Improvements
Add multiple linear regression

Add regularization (Ridge, Lasso)

Deploy as an API

Add tests

Integrate real datasets

Add hyperparameter tuning

👤 Author
Goitseone Rakgomo
AiI/ML engineer
