# 📊 Exploratory Data Analysis (EDA) - Titanic Dataset

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns, relationships, and key factors influencing passenger survival.
The analysis combines **statistical techniques and data visualization** to derive meaningful insights.

---

## 🎯 Objective

* Understand the structure and distribution of the dataset
* Identify trends, correlations, and anomalies
* Extract actionable insights from data
* Build a strong foundation for future predictive modeling

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas** → Data manipulation
* **NumPy** → Numerical operations
* **Matplotlib & Seaborn** → Data visualization

---

## 📂 Dataset Information

* Dataset: Titanic Dataset
* Source: Public dataset (Kaggle / GitHub)
* Features include:

  * Passenger demographics (Age, Sex)
  * Socio-economic status (Pclass, Fare)
  * Family information (SibSp, Parch)
  * Survival outcome (Survived)

---

## 🧹 Data Preprocessing

* Handled missing values:

  * Age → filled using median
  * Embarked → filled using mode
* Removed irrelevant columns (e.g., redundant or zero columns)
* Standardized column names (lowercase formatting)
* Renamed inconsistent column (`2urvived` → `survived`)

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Distribution of Age and Fare
* Survival count visualization
* Identification of skewness in numerical features

### 🔹 Bivariate Analysis

* Survival vs Gender
* Survival vs Passenger Class
* Age vs Survival (boxplot)

### 🔹 Multivariate Analysis

* Pairplot for multiple feature relationships
* Correlation heatmap for feature dependency

---

## 📈 Key Insights

* **Passenger Class Impact**:
  Higher-class passengers had significantly higher survival rates.

* **Gender Influence**:
  Female passengers had a much higher survival probability compared to males.

* **Age Factor**:
  Younger passengers showed slightly better survival chances.

* **Fare Relationship**:
  Higher fare values (wealthier passengers) were positively correlated with survival.

* **Data Skewness**:
  Fare distribution was highly skewed and required transformation.

* **Correlation Findings**:
  No strong multicollinearity observed; moderate relationship between Fare and Pclass.

---

## 📉 Visualization Highlights

* Histograms for distribution analysis
* Countplots for categorical comparison
* Boxplots for outlier detection
* Pairplots for multivariate relationships
* Heatmap for correlation analysis

---

## 🧠 Conclusion

The EDA revealed that survival was influenced by **socio-economic status, gender, and class hierarchy** rather than randomness.
These insights can be leveraged for **predictive modeling and decision-making** in real-world scenarios.

---

## 📁 Project Structure

```
Task-5/
│── EDA_Titanic.ipynb
│── titanic.csv
│── FinalTask 5.pdf
│── README.md
```

---

## 🚀 Future Improvements

* Apply feature engineering
* Build machine learning models (Logistic Regression, Random Forest)
* Perform advanced statistical testing
* Deploy as an interactive dashboard

---

## 🙌 Acknowledgment

This project was completed as part of a **Data Analyst Internship Task** to develop practical skills in data exploration and visualization.

---
