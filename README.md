🔹 Used Bike Prices – Feature Engineering & Exploratory Data Analysis
This project focuses on real-world data cleaning challenges, deep feature engineering, and building a complete analytical pipeline for predicting used bike prices in India.

📌 Project Overview
Domain: Finance / Data Analytics
Difficulty Level: Advanced
Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, VS Code
Dataset Size: 7,857 bike records
Target Variable: price (Indian Rupees)

📊 Dataset Features
Feature	Description
model_name	Bike model with embedded metadata
model_year	Manufacturing year
kms_driven	Total distance driven
owner	Ownership category (first, second, etc.)
location	City of sale
mileage	Fuel efficiency (kmpl)
power	Engine power (converted to BHP)
cc	Engine capacity (engineered feature)
brand	Bike brand (engineered feature)
price	Selling price (Target)


⚙️ Major Work Done

🧹 Data Cleaning
Removed inconsistent units from power, mileage, and kms_driven
Converted power from HP / KW / PS → BHP
Handled missing values using:
Brand-wise mean imputation
Internet reference values for special cases
Standardized brand naming (e.g., BenelliImperiale → Benelli Imperiale)

🏗 Feature Engineering
Extracted Engine CC from model_name using Regex
Derived brand column
Created clean numerical columns from raw messy strings
Ensured correct data types for ML compatibility

📈 Exploratory Data Analysis (EDA)
Distribution analysis of:
Price, Mileage, Power, KMS Driven, CC
Brand-wise and Year-wise trends
Ownership pattern analysis
CC capacity vs Price insights
Outlier detection & skewness handling

🤖 Modeling
Built baseline regression model for price prediction
Split dataset using train_test_split

Evaluated using:
Mean Squared Error (MSE)
R² Score

📊 Key Insights
Most bikes are from 2014–2018
Bajaj & Royal Enfield dominate used-bike market
First-owner bikes have significantly higher resale value
Engine capacities 150cc and 350cc are the most popular
Mileage and CC strongly influence price

🧠 What This Project Demonstrates
✔ Handling real messy datasets
✔ Regex-based feature extraction
✔ Domain-based manual correction strategies
✔ End-to-end professional ML workflow
✔ Finance-driven business insights

📎 Dataset Source
Used Bike Price Dataset – India (Kaggle / Google Drive)
