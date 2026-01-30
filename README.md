🛒 Supermart Grocery Sales

– Retail Analytics A hands-on data analytics and machine learning project using fictional grocery sales data from Tamil Nadu, India. This project demonstrates the full pipeline from data cleaning and visualization to predictive modeling and performance evaluation.

📦 Dataset Overview

Source: Grocery delivery app (fictional)
Scope: Orders placed across cities in Tamil Nadu
Features: Order ID, Customer Name, Category, Sub-Category, City, Region, Sales, Discount, Profit, Order Date, Month, Year.
🧰 Tools & Technologies

Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
Jupyter Notebook / Kaggle
Streamlit (optional for dashboard deployment)
SQL & Excel (for alternate analysis)
🚀 Project Workflow

Data Preprocessing
Handle missing values and duplicates
Convert date columns to datetime format
Extract day, month, and year features
Encode categorical variables using LabelEncoder
Exploratory Data Analysis (EDA)
Sales distribution by category
Time-series trends of sales
Correlation heatmap
Top cities by sales
Monthly and yearly sales breakdown
Feature Engineering
Extracted temporal features
Encoded categorical variables
Selected relevant predictors for modeling
Model Building
Linear Regression to predict sales
Train-test split and feature scaling
Model evaluation using MSE and R²
Visualization
Actual vs Predicted Sales scatter plot
Sales trends by month and year
Top-performing cities and categories
📈 Sample Results

R² Score: 0.82
MSE: 1758.26
Strong predictive performance using basic regression
🔮 Next Steps

Try advanced models: Random Forest, XGBoost
Deploy via Streamlit for real-time analytics
Add interactive filters for city, category, and time
