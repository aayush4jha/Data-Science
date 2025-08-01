# 📊 Frequency Analysis and Probability in Data Science

This project demonstrates how frequency tables, probability calculations, and correlation analysis can be applied to a real-world dataset. The **Titanic dataset** is used for all tasks and visualizations.

---

## 📁 Dataset

**Source:** [Titanic Dataset](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv)  
The dataset contains demographic and survival information of passengers aboard the Titanic.

---

## 📌 Objectives

- Create and analyze frequency tables
- Calculate joint, marginal, and conditional probabilities using contingency tables
- Understand and compute correlations between numeric variables
- Visualize relationships between variables for better interpretation

---

## ✅ Tasks Overview

### Part I: Frequency Table

- Frequency distribution of the `class` variable
  - Absolute frequency
  - Relative frequency (percentage)
  - Cumulative frequency

### Part II: Probability Calculations

- Create a two-way contingency table for `sex` and `survived`
- Compute:
  - **Joint Probability**: P(Sex = female, Survived = 1)
  - **Marginal Probabilities**: P(Sex = female), P(Survived = 1)
  - **Conditional Probabilities**: 
    - P(Survived = 1 | Sex = female)
    - P(Sex = female | Survived = 1)

### Part III: Correlation Analysis

- Choose numeric variables: `age` and `fare`
- Handle missing values
- Compute **Pearson correlation coefficient**
- Visualize the relationship using:
  - `sns.heatmap()`
  - `sns.pairplot()`
  - `plt.scatter()`

### Bonus: Visualization

- Create a stacked bar chart to visualize survival counts across classes
- Identify which class had the highest survival rate

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 📄 Output

- Code for all tasks
- Clean and labeled visualizations
- Explanations and interpretations of the results
- Correlation analysis with insights

---

Explore the notebook to understand how statistical and visual techniques can uncover patterns in data.
