# Car Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the selling price of used cars based on various features such as car age, fuel type, transmission, and ownership history. The objective is to build and evaluate regression-based machine learning models that can accurately estimate car prices from historical data.

This project demonstrates the complete **end-to-end Data Science workflow**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

## 🧠 Problem Statement
Used car pricing depends on multiple factors such as brand, age, fuel type, and transmission. Accurately predicting car prices can help buyers and sellers make informed decisions.

**Goal:**  
Predict the selling price of a car using machine learning regression techniques.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook  

---

## 📊 Dataset
- Dataset: `car data.csv`
- Type: Tabular dataset containing car attributes and selling price
- Target Variable: `Selling_Price`

---

## 🔍 Methodology

### 1. Data Loading
- Loaded dataset using Pandas
- Verified data types and structure

### 2. Exploratory Data Analysis (EDA)
- Analyzed feature distributions
- Studied correlations between independent variables and selling price
- Visualized insights using bar plots, scatter plots, and heatmaps

### 3. Data Preprocessing
- Handled categorical variables using encoding
- Created new features such as **car age**
- Removed irrelevant or redundant columns

### 4. Model Building
Implemented and compared multiple regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 5. Model Evaluation
- Split data into training and testing sets
- Evaluated models using metrics such as **Mean Squared Error (MSE)** and **Root Mean Squared Error (RMSE)**
- Compared performance to select the best model

---

## 📈 Results
- Random Forest Regressor performed better compared to linear models
- Demonstrated improved prediction accuracy due to non-linear learning capability

---

## ✅ Conclusion
- Machine learning models can effectively predict car prices when proper feature engineering and preprocessing are applied.
- Ensemble models like Random Forest capture complex relationships better than linear models.

---

## 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Feature selection optimization
- Deployment as a web application using Flask or FastAPI

---

## ▶️ How to Run
1. Clone the repository
2. Open `Car Price prediction.ipynb` in Jupyter Notebook
3. Run all cells sequentially

---

## 📌 Author
**Prachi Agrawal**  

