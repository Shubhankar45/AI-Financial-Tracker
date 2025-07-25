# 💰 Smart Budget Forecast

An intelligent personal budgeting app built with **Flask**, **PostgreSQL**, and **Machine Learning**.  
It forecasts future expenses using historical transaction data via **Linear Regression** and **Random Forest** models.

---

## 🔍 Features

- 📊 **Expense Forecasting** — Predict monthly spending using ML
- 🧠 **ML Models Used** — Linear Regression, Random Forest, Polynomial Regression
- 🔍 **Category-wise Prediction** — Estimate future spending by category
- 📈 **Insights & Tips** — AI-powered insights based on your habits
- 🧮 **Budget Tracking** — Set and manage monthly category budgets
- 📂 **Transaction History** — Add, edit, and view all financial records
- 🔐 **User Auth** — Secure login, registration, and sessions

---

## ⚙️ Tech Stack

| Layer        | Technology              |
|--------------|--------------------------|
| Backend      | Flask (Python)           |
| Database     | PostgreSQL + SQLAlchemy  |
| ML Models    | scikit-learn             |
| Frontend     | HTML, Bootstrap (Jinja2 templates) |
| Deployment   | Gunicorn                 |
| Hosting      | Replit / Render / Railway compatible |

---

## 🧠 ML Overview

The app fetches monthly aggregated transaction data and uses:

- `RandomForestRegressor` for robust tree-based modeling
- `LinearRegression` for quick, interpretable predictions
- Optional: Polynomial Regression for non-linear patterns

Model selection is **dynamic**, based on historical data quality and performance (`R² score`).

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/smart-budget-forecast.git
cd smart-budget-forecast
