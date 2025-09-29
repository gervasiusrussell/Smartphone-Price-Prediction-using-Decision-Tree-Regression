# 📱 Smartphone Price Prediction using Decision Tree Regression

## 📖 Project Overview

This project applies a **Decision Tree Regression model** to predict smartphone prices based on various features (e.g., RAM, storage, battery power, processor speed, etc.). The goal is to explore how tree-based models can capture non-linear relationships in pricing trends for mobile devices.

---

## ⚙️ Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **Scikit-learn** – Machine Learning (DecisionTreeRegressor, train-test split, evaluation)
* **Pandas & NumPy** – Data preprocessing & feature engineering
* **Matplotlib & Seaborn** – Data visualization

---

## 📊 Workflow

1. **Data Preprocessing**

   * Handle missing values
   * Feature scaling & encoding if necessary
   * Train/test split

2. **Exploratory Data Analysis (EDA)**

   * Correlation between features and smartphone prices
   * Feature importance visualization

3. **Modeling**

   * Decision Tree Regression
   * Hyperparameter tuning (e.g., `max_depth`, `min_samples_split`)

4. **Evaluation**

   * Metrics: MAE, MSE, RMSE, R²
   * Compare training vs testing accuracy to check for overfitting

---

## 📂 Files in Repository

* `Smartphone_regression_decision_tree.ipynb` → Jupyter Notebook with code, visualization, and results.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook Smartphone_regression_decision_tree.ipynb
   ```

---

## 📈 Results

* Decision Tree was able to capture **non-linear patterns** in smartphone prices.
* Identified **key features** influencing prices such as RAM, storage, and processor speed.
* Future improvements could include trying **Random Forest** or **XGBoost** for better generalization.

---

✍️ **Author**: Gervasius Russell
🎓 **Major**: Data Science, BINUS University
