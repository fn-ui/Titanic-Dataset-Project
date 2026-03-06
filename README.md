# Titanic Survival Prediction - Feature Engineering Project

## Project Description

This project analyzes the Titanic passenger dataset to build a predictive
model for survival. The goal is to improve model performance using
data cleaning, feature engineering, and feature selection techniques.

Dataset used: Titanic - Machine Learning from Disaster.

---

## Project Structure

titanic_assignment/
│
├── data/               # Raw dataset files
├── notebooks/          # Jupyter notebook with analysis
├── scripts/            # Python scripts for modular code
├── README.md
└── requirements.txt

---

## Approach

The project follows three main steps:

### 1. Data Cleaning
- Missing values handled
- Outliers inspected
- Data consistency ensured

### 2. Feature Engineering
New features created:
- FamilySize
- IsAlone
- Title
- Deck
- AgeGroup
- FarePerPerson

Transformations:
- One-hot encoding for categorical variables
- Log transformation for skewed data
- Feature scaling

### 3. Feature Selection
Methods used:
- Correlation analysis
- Random Forest feature importance
- Recursive Feature Elimination (RFE)

---

## Key Observations

- Gender (Sex) strongly influences survival.
- Passenger class (Pclass) impacts survival probability.
- Children and women had higher survival rates.
- Passengers traveling with family had slightly better survival chances.

---

## How to Run the Project

1. Install dependencies:

pip install -r requirements.txt

2. Open the notebook:

notebooks/Titanic_Feature_Engineering.ipynb

3. Run the notebook cells sequentially.

---

## Author

## Author

Faith Njeri  
Student, Egerton University  
GitHub: https://github.com/fn-ui
