
# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

## Project Overview
This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset provided by [Kaggle](https://www.kaggle.com/c/titanic/data). The objective is to understand survival patterns by exploring relationships between key features like sex, age, passenger class, and more.

## Dataset
- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)
- **File Used:** `train.csv`
- **Target Variable:** `Survived` (0 = No, 1 = Yes)

## Tasks Performed
- Loaded and examined the dataset.
- Cleaned missing values in:
  - `Age` (filled with median)
  - `Embarked` (filled with mode)
- Dropped:
  - `Cabin` (too many missing values)
  - `PassengerId`, `Name`, `Ticket` (not useful for analysis)
- Converted categorical columns (`Sex`, `Embarked`) into numeric values.
- Performed EDA using Seaborn and Matplotlib visualizations.

##  EDA Visualizations
- ✅ Overall survival count
- ✅ Survival by gender
- ✅ Survival by passenger class
- ✅ Age distribution of passengers
- ✅ Correlation heatmap of numeric features

## Key Insights
- **Females** had a significantly higher survival rate.
- **1st Class** passengers had better survival odds than those in 2nd or 3rd.
- Younger passengers were more likely to survive.
- Features like `Sex`, `Pclass`, and `Fare` had strong correlation with survival.

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run
1. Download `train.csv` from Kaggle.
2. Place the file in your project folder.
3. Run the Python or Jupyter Notebook file containing the analysis code.

## Folder Structure
```
titanic-eda-project/
│
├── train.csv
├── titanic EDA.ipynb
└── README.md
```

##  Author
**Netika Tiwari**
