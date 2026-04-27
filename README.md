# 🤖 DevelopersHub AI/ML Engineering Internship

This repository contains completed tasks for the **DevelopersHub Corporation AI/ML Engineering Internship**.

---

## ✅ Completed Tasks

### Task 2: Stock Price Prediction
**Objective:** Predict the next day's closing price using historical stock data.

| Detail | Info |
|--------|------|
| **Dataset** | Apple Inc. (AAPL) from Yahoo Finance via `yfinance` |
| **Models** | Linear Regression, Random Forest Regressor |
| **Features** | Open, High, Low, Close, Volume, Moving Averages (MA5, MA20), Volatility |
| **Evaluation** | MAE, RMSE, R² Score |

**Key Findings:**
- Random Forest outperformed Linear Regression due to non-linear patterns in stock data
- Moving averages (`MA_5`, `MA_20`) were the most important predictive features
- Stock prediction is inherently uncertain; models are for educational purposes only

---

### Task 3: Heart Disease Prediction
**Objective:** Classify whether a patient is at risk of heart disease based on health metrics.

| Detail | Info |
|--------|------|
| **Dataset** | Heart Disease UCI Dataset (Cleveland) |
| **Models** | Logistic Regression, Decision Tree Classifier |
| **Features** | Age, sex, chest pain type, blood pressure, cholesterol, max heart rate, etc. |
| **Evaluation** | Accuracy, Confusion Matrix, ROC-AUC Curve |

**Key Findings:**
- Logistic Regression achieved strong accuracy on this binary classification task
- Most influential features: `thalach` (max heart rate), `cp` (chest pain type), `ca` (vessel count)
- ROC-AUC score significantly above 0.5, confirming the model outperforms random guessing

---

### Task 6: House Price Prediction
**Objective:** Predict median house prices using property and location features.

| Detail | Info |
|--------|------|
| **Dataset** | California Housing Dataset (built into scikit-learn) |
| **Models** | Linear Regression, Gradient Boosting Regressor |
| **Features** | Median income, house age, rooms, bedrooms, population, lat/lon, engineered features |
| **Evaluation** | MAE, RMSE, R² Score |

**Key Findings:**
- Gradient Boosting significantly outperformed Linear Regression
- `MedIncome` (median income) and geographic location (`Latitude`, `Longitude`) are the strongest predictors
- Engineered features (`BedroomRatio`, `RoomsPerPerson`) improved model performance

---

## 🛠️ Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/developershub-aiml-internship.git
cd developershub-aiml-internship
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

Then open any of the `.ipynb` files to run the tasks.

---

## 📁 Repository Structure

```
📦 developershub-aiml-internship
 ┣ 📓 Task2_Stock_Price_Prediction.ipynb
 ┣ 📓 Task3_Heart_Disease_Prediction.ipynb
 ┣ 📓 Task6_House_Price_Prediction.ipynb
 ┗ 📄 README.md
```

---

## 🧰 Libraries Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical computations |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical plots |
| `scikit-learn` | Machine learning models and evaluation |
| `yfinance` | Fetching live stock market data |

---

*Submitted as part of the DevelopersHub Corporation AI/ML Engineering Internship — Due: 28 April 2026*
