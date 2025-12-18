 # 📊 Regression Analysis: Linear vs Ridge vs Lasso

This project demonstrates and compares **Linear Regression**, **Ridge Regression**, and **Lasso Regression** using Python and scikit-learn. The goal is to understand how regularization impacts model performance, overfitting, and feature importance.

---

## 🚀 Project Overview

Regression models are widely used for prediction tasks, but simple Linear Regression can overfit when features are highly correlated or noisy. To overcome this, **Ridge (L2)** and **Lasso (L1)** regularization techniques are applied and evaluated.

This project:

* Trains Linear, Ridge, and Lasso regression models
* Evaluates them using standard metrics
* Visualizes model performance in a single comparison plot
* Explains insights derived from the results

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📈 Evaluation Metrics

Each model is evaluated using:

* **R² Score** – Measures goodness of fit
* **Mean Squared Error (MSE)** – Penalizes large errors
* **Root Mean Squared Error (RMSE)** – Error in original units

---

## 📊 Visualization

A comparison graph is plotted showing:

* Actual values
* Predictions from Linear Regression
* Predictions from Ridge Regression
* Predictions from Lasso Regression

This helps visually understand bias–variance trade-offs and model stability.

---

## 🔍 Key Insights

* **Linear Regression** may overfit when features are correlated
* **Ridge Regression** reduces overfitting by shrinking coefficients
* **Lasso Regression** performs feature selection by forcing some coefficients to zero
* Ridge works well when all features are relevant
* Lasso is useful when feature selection is needed

---

## 📂 Project Structure

```
├── data.csv
├── regression_models.py
├── evaluation_metrics.py
├── plots.py
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/regression-analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the script

```bash
python regression_models.py
```

---

## 📌 Future Enhancements

* Hyperparameter tuning using GridSearchCV
* Cross-validation
* Adding ElasticNet Regression

---

## 🙌 Acknowledgements

This project is created for learning and demonstrating regression techniques in Machine Learning.

---

⭐ If you found this useful, consider starring the repository!
