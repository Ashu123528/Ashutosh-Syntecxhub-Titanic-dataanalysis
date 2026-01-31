<<<<<<< HEAD

# 🚢 Titanic Survival Analysis

**Exploratory Data Analysis (EDA) Project**

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to understand how different factors such as **gender, age, passenger class, fare, and family size** influenced passenger survival.

The main goal of this project is to practice **data cleaning, visualization, and interpretation** using Python libraries and to build an analysis that is suitable for **college submissions, internships, and beginner data analyst roles**.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset
- Handle missing values using appropriate strategies
- Perform detailed exploratory data analysis (EDA)
- Visualize survival patterns using **Matplotlib and Seaborn**
- Draw meaningful insights from data
- Practice feature engineering on real-world data

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas – data manipulation
- NumPy – numerical operations
- Matplotlib – data visualization
- Seaborn – statistical visualizations
- Jupyter Notebook

---

## 📂 Dataset

- Dataset used: **Titanic Training Dataset (`train.csv`)**
- Each row represents a passenger
- Target variable: `Survived`
  - `0` → Did not survive
  - `1` → Survived

---

## 🔍 Steps Performed in the Project

### 1️⃣ Data Understanding

- Checked dataset shape, columns, and data types
- Reviewed statistical summary to understand distributions
- Identified missing values and outliers

### 2️⃣ Data Cleaning

- Dropped `Cabin` column due to excessive missing values
- Filled missing `Age` values using median
- Filled missing `Embarked` values using mode
- Ensured dataset was clean before visualization

### 3️⃣ Exploratory Data Analysis (EDA)

Performed multiple visualizations to analyze survival patterns:

- Overall survival count
- Survival by gender
- Survival by passenger class
- Survival by embarkation port
- Age distribution of passengers
- Age vs survival
- Fare distribution
- Fare vs survival
- Alone vs family survival comparison
- Correlation heatmap

All graphs were created using **Matplotlib and Seaborn** with proper labels and titles.

### 4️⃣ Feature Engineering

- Created `FamilySize` feature using `SibSp` and `Parch`
- Created `IsAlone` feature to identify solo travelers
- Analyzed how family presence affected survival

---

## 📊 Key Insights

- Female passengers had a significantly higher survival rate than males
- First-class passengers survived more compared to lower classes
- Children had better survival chances
- Higher ticket fare was associated with higher survival probability
- Passengers traveling with family survived more often than those traveling alone

---

## 🧠 What I Learned

- Importance of data cleaning before analysis
- How missing values affect visualizations and insights
- How to use Matplotlib and Seaborn effectively
- How feature engineering can add more meaning to analysis
- How to explain insights clearly using visual evidence

---

## 📁 Project Structure

```
├── Titanic_EDA_Project.ipynb
├── train.csv
└── README.md
```

---

## 📌 How to Run the Project

1. Clone the repository
2. Open Jupyter Notebook
3. Load `Titanic_EDA_Project.ipynb`
4. Make sure `train.csv` is in the same folder
5. Run cells sequentially

---

## 📄 Conclusion

This project helped me strengthen my understanding of **real-world data analysis** using Python.
By combining data cleaning, visualization, and interpretation, I was able to uncover meaningful patterns behind Titanic passenger survival.

---

## 👤 Author

**Ashutosh Singh**
Internship: *[SYNTECXHUB]*

Company -level Data Analysis Project

---
