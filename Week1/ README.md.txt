# Week 1: Titanic Data Cleaning Assignment

## 📋 Project Overview
This project focuses on cleaning and preprocessing the Titanic dataset for machine learning and analysis. It was completed as part of my Machine Learning & AI Internship.

## 📁 Files in This Folder
| File | Description |
|------|-------------|
| `Assignment1.ipynb` | Complete Jupyter notebook with all code |
| `Titanic-Dataset.csv` | Original Titanic dataset |
| `Titanic-Cleaned-Dataset.csv` | Cleaned dataset after preprocessing |
| `picture1.png` | Screenshot of visualizations and results |
| `README.md` | This file - project documentation |

## 🔧 Data Cleaning Steps

### 1. Handling Missing Values
- **Age**: Filled with median (30.0)
- **Fare**: Filled with mean (32.20)
- **Embarked**: Filled with mode ('S')
- **Cabin**: Dropped entirely (too many missing values)

### 2. Encoding Categorical Variables
- **Sex**: LabelEncoder (0 = Female, 1 = Male)
- **Embarked**: LabelEncoder + OneHotEncoder

### 3. Visualizations Created
- Age distribution histogram
- Age by survival comparison
- Age by passenger class boxplot
- Age density plot by survival
- Survival rate by sex
- Survival rate by passenger class

## 📊 Results Summary
- **Original shape**: (891, 12)
- **Cleaned shape**: (891, 16)
- **Missing values**: All handled
- **Dataset status**: Ready for machine learning

## 🛠️ Technologies Used
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📝 Assignments Completed
✅ Assignment 1: Loaded dataset and summarized basic stats (.info(), .describe())
✅ Assignment 2: Handled missing data using mean/median imputation
✅ Assignment 3: Encoded categorical variables using LabelEncoder & OneHotEncoder
✅ Mini Project: Titanic Survival Prediction – Data Cleaning Project

## 🚀 How to Run
1. Open `Assignment1.ipynb` in Jupyter Notebook/Lab
2. Run all cells (Kernel → Restart & Run All)
3. Visualizations will appear automatically
4. Cleaned dataset will be saved as CSV

## 👤 Author
Adrija paul

## 📅 Date
06-09-2026

## 🔗 GitHub Repository
[https://github.com/Adrija05D/skillnexis-internship.git]