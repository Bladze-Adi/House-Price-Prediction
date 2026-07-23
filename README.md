# 🏡 House Price Prediction (EDA & Machine Learning)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Bladze-Adi/House-Price-Prediction/blob/main/house_price_prediction_eda_model.ipynb)

---

## ❓ 1. WHAT (Project Overview)
This project is an end-to-end Machine Learning pipeline that predicts residential house prices based on key property features such as area, number of bedrooms, and location metrics.

* **Target Variable:** House Price
* **Core Task:** Regression / Predictive Modeling
* **Primary Notebook:** `house_price_prediction_eda_model.ipynb`

---

## 🎯 2. WHY (Problem Statement & Purpose)
Real estate pricing is influenced by complex, non-linear relationships across various property features. Accurately estimating house values helps:

* **Buyers & Sellers:** Make fair, data-driven real estate transactions.
* **Real Estate Platforms:** Provide automated valuation estimates (AVMs).
* **Feature Understanding:** Identify which specific property traits (e.g., square footage, location) drive property value up or down the most.

---

## ⚙️ 3. HOW (Methodology & Implementation)

* **Dataset:** Built-in California Housing Dataset (`sklearn.datasets.fetch_california_housing`)

The project follows a structured data science workflow implemented inside the Jupyter Notebook:

### A. Data Preprocessing & Cleaning
* Checked for missing/null values and applied suitable imputation strategies.
* Detected and treated statistical outliers in feature distributions.
* Encoded categorical features and normalized continuous variables.

### B. Exploratory Data Analysis (EDA)
* Analyzed feature correlation using heatmap matrices.
* Visualized distribution of house prices and relationship against square footage using Seaborn and Matplotlib.

### C. Model Development & Evaluation
* Split the dataset into Training (80%) and Testing (20%) sets.
* Applied **Linear Regression** algorithm to establish baseline performance.
* Evaluated model accuracy using metrics like Root Mean Squared Error (RMSE) and $R^2$ Score.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook / Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Bladze-Adi/House-Price-Prediction.git](https://github.com/Bladze-Adi/House-Price-Prediction.git)
