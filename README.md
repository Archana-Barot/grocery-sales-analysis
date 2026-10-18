# grocery-sales-analysis
End-to-end grocery sales analysis and prediction using Random Forest Regressor.
# 🛒 Grocery Sales Prediction & Exploratory Data Analysis (EDA)

An end-to-end data science portfolio project analyzing retail grocery data to uncover key sales drivers and build a predictive machine learning model.

---

## 📌 Project Overview
In the retail and grocery sector, understanding sales performance and predicting future revenue is crucial for inventory management and business strategy. This project explores a dataset of **8,523 products across multiple outlets**, implementing a complete data science workflow from data cleaning and feature engineering to exploratory data analysis (EDA) and machine learning modeling.

---

## 🛠️ Tech Stack & Libraries
* **Python** (Pandas, NumPy)
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (`RandomForestRegressor`, `LabelEncoder`, evaluation metrics)

---

## 🔄 Project Workflow & Methodology

1. **Data Cleaning & Preprocessing:** 
   * Handled missing values using median-based imputation.
   * Cleaned and standardized categorical text and data types.
2. **Feature Engineering:** 
   * Created a custom **`outlet_age`** feature to analyze how the age of a store impacts its performance.
3. **Exploratory Data Analysis (EDA) & KPIs:** 
   * Calculated core business KPIs (Total Sales, Average Sales, Total Items Sold, Average Rating).
   * Built visual charts analyzing sales by *Item Type*, *Outlet Size*, *Fat Content*, *Outlet Location Tier*, and *Establishment Year*.
4. **Machine Learning Modeling:** 
   * Encoded categorical features using `LabelEncoder`.
   * Split data into 80% training and 20% testing sets.
   * Trained a **Random Forest Regressor** to predict product sales.
5. **Model Evaluation & Explainability:** 
   * Evaluated model performance achieving an **$R^2$ Score of 0.4991**.
   * Generated a **Feature Importance** plot to interpret which variables (such as *Item Visibility* and *Item Weight*) drove the model's predictions.

---

## 📊 Key Insights & Findings
* **Top Sales Drivers:** Categories like *Fruits & Vegetables* and *Snack Foods* generated the highest total revenue.
* **Location Impact:** *Tier 3* outlet locations contributed significantly to total store sales.
* **Product Preferences:** *Low Fat* items accounted for a larger share of total sales compared to *Regular* items.
* **Model Insights:** Feature importance analysis revealed that *Item Visibility* and *Item Weight* played the most dominant roles in the Random Forest Regressor's predictive decisions.

---

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/Archana-Barot/grocery-sales-analysis.git

2. Install the required dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
4. Open the Jupyter Notebook and run the cells sequentially:
   jupyter notebook
   
