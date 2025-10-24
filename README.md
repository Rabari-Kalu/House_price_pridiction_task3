# House_price_pridiction_task3
Implement and understand simple & multiple linear regression.
# Multiple Linear Regression — Housing Price Prediction

This project demonstrates the implementation of **Multiple Linear Regression (MLR)** using Python and Scikit-learn to predict house prices based on multiple independent variables.

---

##  **Objective**
To build a predictive model that estimates the **price of a house** using multiple features such as area, bedrooms, and furnishing details.

---

##  **Project Workflow**

###  Import and Explore the Dataset
- Load dataset (`Housing.csv`) using **Pandas**
- Display shape, info, and missing values
- Preview first few rows to understand structure
df = pd.read_csv("Housing.csv")
print(df.info())
print(df.head())
