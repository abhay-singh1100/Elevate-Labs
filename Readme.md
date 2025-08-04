# Titanic Dataset Analysis

📁 **File**: `task1/titanic.ipynb`  
📊 **Project Type**: Exploratory Data Analysis (EDA) & Preprocessing  
🧠 **Goal**: Understand the factors influencing passenger survival on the Titanic.

---

## 📝 Overview

This project performs exploratory data analysis on the Titanic dataset using Python and several essential data science libraries. The dataset includes demographic, ticket, and survival details of Titanic passengers.

---

## 🎯 Objective

- Explore the Titanic dataset to understand its structure and content.
- Clean and preprocess the data to make it suitable for analysis.
- Apply basic visualization and statistical methods to uncover survival patterns.
- Derive insights from the data that highlight key survival factors.

---

## 📂 Dataset Description

The Titanic dataset contains **891 rows** and **12 columns**, representing various attributes of the passengers.  

### 🔑 Features:

- `PassengerId`: Unique identifier for each passenger
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## ⚙️ Methodology

### 1. **Data Import**
- The dataset is loaded using **pandas** for easy manipulation.

### 2. **Data Cleaning**
- The `Fare` column is converted to an integer type for consistency.
- Missing values and anomalies (if any) are identified and addressed.

### 3. **Data Preprocessing**
- The categorical `Sex` column is transformed using **OneHotEncoding** from **scikit-learn**.

### 4. **Data Exploration**
- Descriptive statistics are generated for numerical features.
- **Box plots** and visualizations are used to explore relationships (e.g., Fare vs. Survival).

---

## 🔍 Key Insights

- Passengers who paid higher fares had a higher survival rate.
- One-hot encoding of categorical features (like `Sex`) allows the data to be used in machine learning models or deeper statistical analysis.

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

---

## 🧾 Code Structure

The notebook is organized into the following logical sections:

1. **Importing Libraries**
2. **Loading the Dataset**
3. **Data Cleaning**
4. **Data Preprocessing**
5. **Exploratory Data Analysis (EDA)**

---

## 📌 Notes

- The project sets a foundation for further predictive modeling (e.g., using logistic regression or decision trees).
- It demonstrates good practices in preprocessing and visualization for beginners.

---

## 📎 Reference

- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
