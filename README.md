## 📌 Internship Task - Data Analyst Role

# Task 4:  Exploratory Data Analysis (EDA)


This project presents an in-depth exploratory data analysis (EDA) of the Titanic dataset using Python (Pandas, Seaborn, Matplotlib). It aims to uncover patterns, relationships, and insights that can aid in understanding survival trends.

---

## 📁 Dataset

- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **File used**: `train.csv`

---

## 🧠 Objectives

- Apply `.info()`, `.describe()`, and `.value_counts()` for initial exploration.
- Use `seaborn` to generate meaningful plots:
  - `pairplot()` and `heatmap()` for relationships
  - Histograms, boxplots, and scatterplots
- Identify trends and correlations (e.g. gender, class, fare, age).
- Write observations for each visualization.
- Provide a summary of findings.

---

## 🛠 Tools and Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

---

## 🛠 Code (Run without setup using Google Colab)

🔗 Google Colab Link:
https://colab.research.google.com/drive/1CvdvCrIfgye0-tRtzUDQT8sRs3-d_RYJ?usp=sharing

---

## 📊 Key Plots & Observations

### 1. Survival Count
- Shows imbalance in survival (many more non-survivors).

### 2. Age Distribution
- Most passengers were between 20–40 years old.
- Right-skewed age distribution.

### 3. Age by Passenger Class
- 1st class passengers tend to be older than 2nd/3rd class.

### 4. Fare vs Age (Scatterplot by Survival)
- Higher fare passengers had a better chance of survival.

### 5. Correlation Heatmap
- Strong negative correlation between Pclass and Fare.
- Survived correlates positively with Fare, negatively with Pclass.

### 6. Pairplot
- Fare and Age are skewed.
- Survivors cluster among younger and higher-fare groups.

---

## 📝 Summary of Findings

1. Females had a significantly higher survival rate than males.
2. 1st class passengers were more likely to survive than 2nd or 3rd class.
3. Higher fare was positively associated with survival.
4. Younger children had a better chance of survival.
5. Most passengers were in the 20-40 age range.
6. Age and Fare are not normally distributed - they are skewed.
7. Embarked location shows some influence on survival, especially from port 'C'

---
