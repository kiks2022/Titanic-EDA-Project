# AnalystLab Africa — AI Internship Program
### Week 1 & 2: AI Foundations & Data Preparation

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## About This Project
This repository contains my work for **Week 1 & 2** of the AnalystLab Africa AI Internship Program. The goal was to build a strong foundation in AI by cleaning real-world data and discovering patterns through exploratory data analysis (EDA).

---

## Dataset
**Titanic Dataset** — [Kaggle Link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

- 891 passengers
- 12 columns of information per passenger
- Target column: `Survived` (0 = did not survive, 1 = survived)

---

## What I Did

### 1. Data Cleaning
| Problem | Solution |
|---|---|
| Age: 177 missing values (19.87%) | Filled with median age (28) |
| Cabin: 687 missing values (77.1%) | Replaced with `HasCabin` column (1/0) |
| Embarked: 2 missing values | Filled with most common port (S) |
| Useless columns | Dropped `PassengerId`, `Name`, `Ticket` |

**Result:** Cleaned dataset with 9 useful columns, zero missing values.

### 2. Exploratory Data Analysis (EDA)
Made 5 charts to answer key questions about survival patterns.

---

## Key Findings

### Overall Survival
- Only **38.4%** of passengers survived
- 549 passengers died, 342 survived

### Gender
- Women survived at **74%**
- Men survived at only **19%**
- "Women and children first" was very real

### Passenger Class
- 1st class (rich): **63%** survived
- 2nd class (middle): **47%** survived
- 3rd class (poor): **24%** survived

### Age
- Children under 10 had the highest survival rates
- Most non-survivors were adults aged 20–40

### Strongest Predictors of Survival
Based on the correlation heatmap: **Sex** and **Pclass** are the two strongest predictors of whether a passenger survived.

---

## Conclusion
> Your wealth and your gender determined whether you lived or died on the Titanic.
> Being a woman in 1st class gave you the best chance of survival.
> Being a man in 3rd class gave you the worst.

---

## Files in This Repository

| File | Description |
|---|---|
| `cleaned_titanic.csv` | Cleaned dataset ready for modeling |
| `chart1_survival.png` | Overall survival count |
| `chart2_gender.png` | Survival rate by gender |
| `chart3_class.png` | Survival rate by passenger class |
| `chart4_age.png` | Age distribution of survivors |
| `chart5_heatmap.png` | Correlation heatmap |
| `titanic_summary.txt` | Written summary of insights |

---

## Tools Used
- **Python 3.10**
- **Pandas** — data loading and cleaning
- **NumPy** — numerical operations
- **Matplotlib** — charts and visualizations
- **Seaborn** — styled charts and heatmap
- **Google Colab** — cloud notebook environment

---

## About
**Intern:** [Your Name Here]  
**Program:** AnalystLab Africa AI Internship  
**Week:** 1 & 2 — AI Foundations & Data Preparation  
**Deadline:** 17th May 2026
