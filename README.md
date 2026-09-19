#  Big Mart Sales Prediction using Machine Learning

An end-to-end **Machine Learning Regression** project that predicts product sales for Big Mart outlets using historical retail data. The project includes data cleaning, feature engineering, exploratory data analysis (EDA), model building with **XGBoost Regressor**, and performance evaluation using Python and Scikit-learn.

##  Project Overview

Retail businesses rely on accurate sales forecasting for inventory management and business planning. This project analyzes product and outlet characteristics to predict future sales and identify the factors that most influence product performance.

##  Objectives

* Import and preprocess Big Mart sales data
* Handle missing values and inconsistent entries
* Perform exploratory data analysis (EDA)
* Encode categorical variables
* Train a machine learning regression model
* Evaluate prediction accuracy and visualize results

##  Tech Stack

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **XGBoost**
* **Jupyter Notebook**

##  Project Workflow

### 1. Data Collection & Understanding

* Imported the Big Mart dataset
* Explored dataset dimensions and data types
* Identified numerical and categorical features
* Checked missing values and duplicates

### 2. Data Cleaning

* Filled missing values in `Item_Weight`
* Handled missing `Outlet_Size` values
* Corrected inconsistent categories in `Item_Fat_Content`
* Prepared a clean dataset for modeling

### 3. Exploratory Data Analysis (EDA)

Analyzed important variables including:

* Item visibility
* Item weight
* Item type
* Fat content
* Outlet size and location
* Outlet establishment year
* Sales distribution

### 4. Feature Engineering

* Label encoded categorical variables
* Created feature matrix and target variable
* Split data into training and testing datasets

### 5. Model Training & Evaluation

Built an **XGBoost Regressor** to predict `Item_Outlet_Sales` and evaluated its performance using regression metrics.

##  Visualizations Included

*  Sales Distribution Histogram
*  Correlation Analysis
*  Outlet-wise Sales Comparison
*  Item Type Analysis
*  Feature Importance (XGBoost)
*  Actual vs Predicted Sales Plot

## Repository Structure

```text
Big-Mart-Sales-Prediction/
│
├── Big Mart Sales Prediction.ipynb   # Complete ML notebook
├── README.md                         # Project documentation
└── Train.csv                         # Big Mart sales dataset
```

##  Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Categorical Encoding
* Regression Modeling
* XGBoost Algorithm
* Model Evaluation & Visualization

##  Author

**Afzal Karjikar**

B.Tech in Computer Science (AI & ML)

Aspiring Data Analyst | Machine Learning Enthusiast

---

### ⭐ If you found this project useful, consider giving the repository a Star on GitHub!
