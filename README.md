# 🚢 Exploratory Data Analysis of Titanic Dataset using Python

## 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and key factors influencing passenger survival. The analysis leverages statistical techniques and data visualization to extract meaningful insights from raw data.

The goal is to understand how different features such as age, gender, passenger class, and fare impacted survival outcomes.

---

## 🎯 Objectives

* Analyze survival distribution across different passenger groups
* Identify relationships between features (age, sex, class, fare)
* Handle missing data and clean the dataset
* Perform univariate and bivariate analysis
* Generate actionable insights using visualization

---

## 🛠️ Tools & Technologies

* Python
* Pandas (Data Manipulation)
* NumPy (Numerical Computing)
* Matplotlib & Seaborn (Data Visualization)
* Jupyter Notebook

---

## 📂 Dataset Description

The dataset contains information about Titanic passengers, including:

* PassengerId
* Survived (Target Variable)
* Pclass (Ticket Class)
* Name, Sex, Age
* SibSp (Siblings/Spouses aboard)
* Parch (Parents/Children aboard)
* Fare
* Embarked (Port of Embarkation)

---

## 🔍 Steps Performed

### 1. Data Cleaning

* Handled missing values in Age and Embarked
* Removed irrelevant columns where necessary

### 2. Univariate Analysis

* Distribution of Age, Fare
* Count plots for categorical variables like Gender and Class

### 3. Bivariate Analysis

* Survival rate vs Gender
* Survival rate vs Passenger Class
* Age distribution vs Survival

### 4. Data Visualization

* Bar plots, histograms, heatmaps
* Correlation matrix to identify feature relationships

---

## 📊 Key Insights

* Female passengers had a significantly higher survival rate than males
* Passengers in 1st class had better survival chances compared to lower classes
* Younger passengers had relatively higher survival probability
* Fare is positively correlated with survival (higher fare → higher survival rate)

---

## 📈 Conclusion

The analysis highlights that socio-economic factors (class, fare) and demographics (age, gender) played a crucial role in survival during the Titanic disaster. Data visualization helped uncover these hidden patterns effectively.

---

## 📁 Project Structure

```
Task-5/
│
├── notebook/
│   └── Task5.ipynb
│
├── data/
│   └── titanic.csv
│
├── report/
│   └── FinalTask5.pdf
│
└── README.md
```

---

## 👤 Author

Prem N Gowda
