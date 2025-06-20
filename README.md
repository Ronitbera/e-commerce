# E-commerce Furniture Dataset 

This project involves end-to-end data analysis and modeling on a furniture dataset from an e-commerce platform. It includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, and deployment using Python.

---

## 📊 Project Overview

The dataset contains product-level information, including:
- Product titles and categories
- Prices (original and discounted)
- Discounts and sales volume
- Shipping options and promotional tags

The main goal is to extract business insights and build a model to predict product sales performance.

---

## 🛠️ Tools & Technologies Used

| Tool / Library         | Purpose                                      |
|------------------------|----------------------------------------------|
| **Python**             | Core language for all analysis and modeling  |
| **Pandas, NumPy**      | Data cleaning and preprocessing               |
| **Matplotlib, Seaborn**| Visualizations for exploratory data analysis |
| **Scikit-learn**       | Machine learning (Random Forest Regressor)   |
| **Jupyter Notebook**   | Code development and experimentation         |
| **Streamlit**          | App deployment and interactive user interface |
| **Joblib**             | Saving the trained model for reuse           |

---

## 📌 Project Features

- ✅ **Data Cleaning**
  - Handling missing values
  - Removing duplicates and formatting inconsistencies

- 🔍 **Exploratory Data Analysis (EDA)**
  - Category-wise sales trends
  - Impact of discounts and price on sold units
  - Shipping influence on sales

- 🛠️ **Feature Engineering**
  - Derived fields like `discount_pct`, `price_per_word`, etc.
  - Categorical and numerical encoding for modeling

- 🤖 **Model Training**
  - Random Forest Regressor
  - Performance metrics: MAE, RMSE, R² Score

- 🚀 **Deployment**
  - Streamlit app for real-time prediction based on input fields
  - Clean interface to test different price/discount strategies

